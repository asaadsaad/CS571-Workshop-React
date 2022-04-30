# CS571 - Workshop - React Hooks
Create a React application that shows first a text input to read the user fullname, once users submit their names they see a header and two buttons:
* Header Component: Welcome {fullname} (to be displayed at all time)
* Button: `List Students` component (default)
* Button: `Add New Student` component  
  
The buttons is to toggle (show/hide) the components above, only one component will be displayed at a time, the `List Students` component is displayed by default.

`Add New Student`: This component has several fields as follows:
* Name (Input) with the placeholder 'name'. 
* Email (Input) with the placeholder 'email'. 
* ID (text): It is a random number that is changed every 5 seconds.
* Submit (button): When hitting the submit button, the email should be verified to be unique and saved in a global state and `LocalStorage`. After successful submission the application will switch to display `List Students` component.

`List Students`: To list all students.  
* Display a table that contains student names and emails (from state) with a button to delete every student.   
* Deleting a student will remove the student from state and `LocalStorage`.

**Notes:**
* All components should be function-based.
* All data should be saved in a global state and `LocalStorage`. 
* The data should be loaded to global state when users open the application. 
* The data should always be synched between `LocalStorate` and the global state.
* Use a Reducer function to manage your application state and write up all necessary actions.
* Remember to respect the code honor submission policy. All written code must be original. Presenting any code as one’s own work when it came from another source is plagiarism.
* This workshop will be graded. The deadline to submit your code is 8:00 PM.

*Optional: Create a backend app to persist the application data at the server.*
