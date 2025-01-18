TOC:
- home page
- dashboard page
- to-do page
- in progress page
- completed page
- details page
- creation page
- register page
- login page


  The home page of my task management app uses a simple navbar, jumbotron and card combo layout to welcome users. A paragraph follows the heading explaining a bit about the app. The
three cards highlight a reason for using this app over other task managers.

  The dashboard page has a two card horizontal layout. The first card lists out three categories: To-do, In Progress, and Completed. The next card lists out all of the tasks from the
to-do and in progress pages. The tasks are labeled with their respective task page.

  The to-do page lists out the tasks in cards. Each card includes a heading, a paragraph, and two buttons. The tasks have two buttons, one marked 'Mark Complete' and the other marked
'Delete'.

  The in progress page is similar in layout to the to-do page. The categories list on the left and the task list on the right side. The tasks have two buttons, one marked 'Mark Complete'
and the other marked 'Delete'.

  The completed page is the same as the past two pages. The categories list on the left and the task list on the right side. The tasks have two buttons, one marked 'Mark Complete' and
the other marked 'Delete'.

  The details page takes a closer look to a specific task. It uses a two-column card layout. The left column gives you the details of the specific task while the right column allows you
to edit the task.

  The creation page is where the user can add a new task. The card used on this page is simple and holds two fields. The first field is for a task title and the second field is for the
task description. There is an 'Add Task' submit button at the end.

  The register page allows the user to register a new account. The fields included in this card are: 'Full Name', 'Email Address', 'Password', and 'Confirm Password'. Each field on
this card uses validation. I added a 'novalidate' attribute to the form element on this page so as to disable the browser's validation. The form element also dons the 'was-validated'
class to trigger Bootstrap's visual feedback mechanism. The class 'invalid-feedback' has been included with every field to provide the user with feedback on how to fix an error. The
fields also have the class 'is-valid' so that bootstrap can give a green border for fields that have met the requirements of validation. For example, the email address field will not
turn green until an '@' symbol is present in the field.

  The login/authentication page is a simple card with two fields and a login button. The two fields are username and password. The form element has a class of 'needs-validation' and the
fields a class of 'invalid-feedback'. 
  
