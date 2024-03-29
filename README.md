# React Todo App

This is a simple todo app built with React. It allows you to create and delete tasks. 

## Features

This application covers the following concepts of React:

- Writing React Component Reusability: The app uses functional components and custom hooks to reuse logic and UI elements across the app.
- Passing Data To React Components Dynamically: The app uses props to pass data from parent components to child components handlers for adding, deleting.
- Rendering React Lists Dynamically: The app uses the map method to render a list of tasks based on the tasks array. It also uses the key prop to identify each task item uniquely.
- Handling Data using React State: The app uses the useState and useReducer hooks to manage the state of the tasks array, the filter state, and the input value. It also uses the useEffect hook to persist the tasks array in the local storage.
- Creating and adding user Input to React Form: The app uses a controlled input component to handle the user input for adding and editing tasks. It also uses the onSubmit event to prevent the default behavior of the form and call the handler for adding or editing tasks.
- Passing React Functions through props: The app passes functions as props to child components, such as the handlers for adding, editing, deleting, and toggling tasks. It also uses the useCallback hook to memorize the functions and prevent unnecessary re-rendering of the child components.
- Understanding React Keys: The app uses the id property of each task object as the key prop for each task item. This helps React to identify which items added, or removed.
- Deleting items using React Functionality: The app uses the filter method to delete a task from the tasks array by removing the task object that matches the id of the task to be deleted.
- React conditional Rendering: The app uses conditional rendering to show or hide UI elements based on the state of the app, such as the task count, the clear completed button, and the edit input.
