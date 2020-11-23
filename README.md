# Final_Project

Full Todo List
Project Standards:

Students will use submit events to capture user input.
Students will use variables to store information needed by their application and keep track of their program’s state.
Students will use conditionals to control what's displayed to the dom.
Project Task

You will be building a full todo list in the browser. It should be able to add todos, check todos off as complete, and delete todos.

Display a form to the user to add todos.
When a user types a todo into the form and hits submit, the following should happen:
A new todo should be displayed below any previous todos
Every todo in the list should have a check button next to it to check off the todo and mark it complete
Clicking the check should change the todo in someway, either marking it green or perhaps crossing it out. Check out this link here (Links to an external site.) for some inspiration.
Every todo should have an x to the right that will delete the todo.
Clicking the x should remove the todo from the page.
You'll need to attach a submit event listener to todo form and click event listeners to the check and x for each todo.
Your JavaScript code will form the conditional logic to determine whether a todo should be displayed as complete or incomplete.
Recommended Implementation:

Individual todos should be represented in an object with a text key and a complete key (the complete key should be a boolean true or false).
Individual todo objects should be stored inside an array, making an array of objects.
Representing the above in your JavaScript makes the project much easier rather than stressing about the HTML and the click events.
