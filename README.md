# React Todo App

A simple and efficient Todo application built with React. This project demonstrates the use of modern React features such as hooks, context API, and local storage for state persistence.

## Features

* Add new todos
* Edit existing todos
* Delete todos
* Mark todos as completed
* Persistent storage using localStorage
* Clean and responsive UI

## Technologies Used

* React
* JavaScript (ES6+)
* Tailwind CSS
* Context API

## Project Structure

```
react-todo/
│
├── src/
│   ├── components/
│   │   ├── TodoForm.jsx
│   │   └── TodoItem.jsx
│   │
│   ├── Contexts/
│   │   └── TodoContext.js
│   │
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
│
├── public/
├── package.json
└── README.md
```

## Installation

1. Clone the repository:

```
git clone https://github.com/MAR-ARIF/react-todo.git
```

2. Navigate to the project directory:

```
cd react-todo
```

3. Install dependencies:

```
npm install
```

4. Start the development server:

```
npm run dev
```

## Usage

* Enter a task in the input field and click "Add" to create a new todo.
* Click the edit button to modify a todo.
* Use the checkbox to mark a todo as completed.
* Click the delete button to remove a todo.

## State Management

This project uses the Context API to manage global state across components. The main operations include:

* Adding a todo
* Updating a todo
* Deleting a todo
* Toggling completion status

## Data Persistence

Todos are stored in the browser's localStorage. This ensures that data is retained even after refreshing the page.

## Known Issues

* Editing a todo requires proper initialization of input state.
* Ensure correct handling of toggle functionality with todo IDs.


## License

This project is open source and available under the MIT License.
