### Use Case #1
- **Actors**: User
- **Goal/Purpose**: Create a new task
- **Trigger**: User submits a task creation request
- **Preconditions**: User must provide a task title
- **Post-conditions**: A new task is created with a unique ID and marked as "incomplete"
- **Priority**: High

### Use Case #2
- **Actors**: User
- **Goal/Purpose**: View all tasks
- **Trigger**: User requests to see all tasks
- **Preconditions**: None
- **Post-conditions**: A list of all tasks is returned containing ID, title, description, completion status, and creation date
- **Priority**: High

### Use Case #3
- **Actors**: User
- **Goal/Purpose**: Mark a task as complete
- **Trigger**: User updates task status to complete
- **Preconditions**: The task must exist with a provided unique identifier
- **Post-conditions**: Task status is updated to "complete" and details are returned
- **Priority**: High
