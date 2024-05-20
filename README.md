# TaskManager
Start Application
  Display Main Menu
  While Application is Running
    Display Options: Add Task, Edit Task, Delete Task, View Tasks, Set Priorities, Mark as Complete, Exit
    Get User Choice
    If Choice is Add Task
      Prompt User for Task Details: Title, Description, Due Date, Priority
      Save Task
    Else If Choice is Edit Task
      Display List of Tasks
      Prompt User to Select Task to Edit
      Prompt User for New Details
      Update Task
    Else If Choice is Delete Task
      Display List of Tasks
      Prompt User to Select Task to Delete
      Delete Task
    Else If Choice is View Tasks
      Display List of Tasks Sorted by Priority and Due Date
    Else If Choice is Set Priorities
      Display List of Tasks
      Prompt User to Select Task
      Prompt User for Priority Level
      Update Task Priority
    Else If Choice is Mark as Complete
      Display List of Tasks
      Prompt User to Select Task to Mark as Complete
      Update Task Status
    Else If Choice is Exit
      Exit Application
End Application
