Input
 The mobile app lets users interact by entering a task (todo) into a text input box.  To send it, they then press the "Add Todo" button.  Other operations consist of selecting tab choices to filter which todos are visible, tapping "Done" to indicate a job finished, and "Delete" to delete a task.


 Process
 A new todo submitted adds to an array of todos under app state control.  Every todo has a title, a unique ID, and a completed status.  React Native components alter in real time depending on state changes.  A filter state controls tab filtering, which defines the subset of todos displayed.  Tapping "Done" changes the state of completion.  Tapping "Delete" deletes the todo from the array.  Console logging monitors every activity.

 Output
 Based on user interactions and chosen criteria, the app shows a live-updating list of todos.  The UI changes correspondingly as jobs are added, finished, or deleted.  The tab bar lets you toggle between views: all tasks, completed tasks, or just unfinished ones.  Console logs assist in debugging and user action comprehension by displaying new, toggled, or deleted todos.