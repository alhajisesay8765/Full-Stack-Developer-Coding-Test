# Full-Stack-Developer-Coding-Test
# Front-End Section A
# Task Management

A simple task management component built with React.

## Description

Task Manager is a React component that allows users to manage tasks. Users can add new tasks, mark tasks as completed or incomplete, and delete tasks from the list.

## Installation

To use the Task Manager component in your project, follow these steps:

1. Copy the `TaskManager.js` file into your project directory.
2. Import the `TaskManager` component in your React application.
3. Use the `TaskManager` component within your application to manage tasks.

## Usage

Here's how you can use the `TaskManager` component in your React application:

```jsx
import React from 'react';
import TaskManager from './TaskManager';

const App = () => {
  return (
      <div>
            <TaskManager />
                </div>
                  );
                  }

                  export default App;


# Back-End
# Django Task Manager API

This Django application provides a RESTful API for managing tasks. It allows users to create, update, delete, and view tasks.

## Features

- Create tasks with a title, description, and completion status.
- Update task details and mark tasks as completed.
- Delete tasks from the database.
- Retrieve a list of all tasks or view details of individual tasks.

## Technologies Used

- Django: A high-level Python web framework for rapid development.
- Django REST Framework: A powerful toolkit for building Web APIs in Django.
- PostgreSQL: An open-source relational database management system.

## Installation

1. Clone the repository:git clone https://github.com/alhajisesay8765/Full-Stack-Developer-Coding-Test.git
2. Install dependencies:

3. Configure the database settings in `backend_api_project/settings.py` according to your PostgreSQL setup.

4. Run database migrations:


5. Start the Django development server:


6. Access the API endpoints in your browser or via tools like Postman.

## API Endpoints

- **GET /tasks/**: Retrieve a list of all tasks.
- **GET /tasks/:id/**: Retrieve details of a specific task.
- **POST /tasks/**: Create a new task.
- **PUT /tasks/:id/**: Update details of a specific task.
- **DELETE /tasks/:id/**: Delete a specific task.

## Contributing

Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

