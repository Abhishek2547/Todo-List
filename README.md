# Todo-App

This is a simple Todo application built with React. It allows users to add, edit, delete, and mark tasks as complete. The application also persists data in local storage.

## Features

- Add new tasks: Quickly add new tasks to your todo list.
- Edit existing tasks: Modify tasks as needed.
- Delete tasks: Remove tasks that are no longer needed.
- Mark tasks as complete/incomplete: Easily toggle the completion status of tasks.
- Persist tasks in local storage: All tasks are saved in the browser's local storage, so they remain even after refreshing the page.

## Components

- TodoWrapper: Manages the state of the todo list and renders the list of todos.
- TodoForm: Form to add new tasks.
- EditTodoForm: Form to edit existing tasks.
- Todo: Component to display individual tasks.
- TodoWrapperLocalStorage: An extended version of TodoWrapper with local storage integration.

## Setup and Installation

1. Clone the repository

      git clone https://github.com/yourusername/todo-app.git
   cd todo-app
   

2. Install dependencies

      npm install
   

3. Run the application

      npm start
   

   The application will run on http://localhost:3000.

## Usage

1. Add a Task
   - Enter a task in the input field and click the "Add Task" button.
   - The new task will appear in the list of todos.

2. Edit a Task
   - Click the "Edit" button next to a task.
   - Modify the task in the input field that appears and click the "Update Task" button.

3. Delete a Task
   - Click the "Delete" button next to a task to remove it from the list.

4. Mark a Task as Complete/Incomplete
   - Click the "Complete" button next to a task to toggle its completion status.

## Local Storage Integration

The TodoWrapperLocalStorage component extends the functionality of TodoWrapper by saving the todos in local storage. This ensures that the tasks persist even after the browser is refreshed or closed.

## Project Structure

- src/components
  - Todo.js: Displays individual tasks with options to edit, delete, or mark as complete.
  - TodoForm.js: Form to add new tasks.
  - EditTodoForm.js: Form to edit existing tasks.
  - TodoWrapper.js: Manages the state and renders the list of todos.
  - TodoWrapperLocalStorage.js: Extends TodoWrapper with local storage integration.

## Dependencies

- React: A JavaScript library for building user interfaces.
- uuid: For generating unique IDs for tasks.

## Contributing

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/fooBar).
3. Commit your changes (git commit -am 'Add some fooBar').
4. Push to the branch (git push origin feature/fooBar).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License.