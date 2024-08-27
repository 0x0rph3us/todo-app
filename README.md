# React + Vite

How the App Works

1. App Component: This is the main component that manages the state of the to-do list.
   It handles adding, completing, and removing to-dos. The state is passed down to child components as props.
2. TodoForm Component: This component contain a simple form with an input field. When
   the form is submitted, it calls the 'addToDo' function passed from the 'App' component to add a new task.
3. TodoList Component: This component renders the list of to-dos. It maps over the 
   'todos' array and renders a 'TodoItem' for each to-do.
4. TodoItem Component: Each to-do item is displayed here, along with buttons to mark
   the to-do as completed or remove it.