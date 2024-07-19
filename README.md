# E-Commerce Application

This project has an e-commerce application where I have managed the operations such as Adding, Removing, and Updating cart based on some dummy data. The intention was to learn the best practices as shared below! 

## Table of Contents

1. [Managing State to Switch Between Components](#managing-state-to-switch-between-components)
2. [Collecting User Input with Refs & Forwarded Refs](#collecting-user-input-with-refs--forwarded-refs)
3. [Handling Project Creation & Updating the UI](#handling-project-creation--updating-the-ui)
4. [Validating User Input & Showing an Error Modal via useImperativeHandle](#validating-user-input--showing-an-error-modal-via-useimperativehandle)
5. [Styling the Modal via Tailwind CSS](#styling-the-modal-via-tailwind-css)
6. [Making Projects Selectable & Viewing Project Details](#making-projects-selectable--viewing-project-details)
7. [Handling Project Deletion](#handling-project-deletion)
8. [Adding "Project Tasks" & A Tasks Component](#adding-project-tasks--a-tasks-component)
9. [Managing Tasks & Understanding Prop Drilling](#managing-tasks--understanding-prop-drilling)
10. [Understanding Prop Drilling & Project Overview](#understanding-prop-drilling--project-overview)
11. [Prop Drilling: Component Composition as a Solution](#prop-drilling-component-composition-as-a-solution)
12. [Introducing the Context API](#introducing-the-context-api)
13. [Creating & Providing The Context](#creating--providing-the-context)
14. [Consuming the Context](#consuming-the-context)
15. [Linking the Context to State](#linking-the-context-to-state)
16. [A Different Way Of Consuming Context](#a-different-way-of-consuming-context)
17. [What Happens When Context Values Change?](#what-happens-when-context-values-change)
18. [Migrating the Entire Demo Project to use the Context API](#migrating-the-entire-demo-project-to-use-the-context-api)
19. [Outsourcing Context & State Into a Custom Hook](#outsourcing-context--state-into-a-custom-hook)
20. [Introducing the useReducer Hook](#introducing-the-usereducer-hook)
21. [Dispatching Actions & Editing State with useReducer](#dispatching-actions--editing-state-with-usereducer)



### Managing State to Switch Between Components

Learned how to manage state effectively to switch between different components in a React application. Best practice includes lifting state up to the nearest common ancestor to avoid prop drilling.



### Collecting User Input with Refs & Forwarded Refs

Explored techniques for collecting user input using React Refs and forwarded Refs. Best practice involves using Refs sparingly and only when necessary, as they break the declarative nature of React.



### Handling Project Creation & Updating the UI

Understood how to handle project creation and update the user interface accordingly. Best practice includes managing side effects using hooks like `useEffect` for a clean and predictable UI update.



### Validating User Input & Showing an Error Modal via useImperativeHandle

Learned to validate user input and display an error modal using the `useImperativeHandle` hook. Best practice is to encapsulate imperative logic in custom hooks to maintain component readability and reusability.



### Styling the Modal via Tailwind CSS

Discovered how to style a modal component using Tailwind CSS for a consistent and responsive design. Best practice is to use utility-first CSS frameworks like Tailwind to avoid conflicts and ensure maintainability.


### Making Projects Selectable & Viewing Project Details

Understood how to make projects selectable and view their details within the application. Best practice involves using controlled components for selection to keep state predictable and manageable.


### Handling Project Deletion

Learned how to handle the deletion of projects efficiently within a React application. Best practice includes providing confirmation dialogs to prevent accidental deletions and managing state updates optimistically.


### Adding "Project Tasks" & A Tasks Component

Found out how to add "Project Tasks" and implement a corresponding tasks component. Best practice is to break down the UI into smaller, reusable components and manage state locally where possible.


### Managing Tasks & Understanding Prop Drilling

Delved into managing tasks and the concept of prop drilling in React to ensure effective data flow. Best practice is to use Context API or state management libraries like Redux to avoid excessive prop drilling.


### Understanding Prop Drilling & Project Overview

Learned about prop drilling and how it affects component structure and data flow. Best practice involves avoiding deep prop chains by using Context API or other state management solutions.


### Prop Drilling: Component Composition as a Solution

Explored how component composition can be a solution to prop drilling. Best practice is to design components that can be composed together, promoting reusability and reducing the need for prop drilling.


### Introducing the Context API

Got introduced to the Context API and how it helps in managing global state. Best practice includes using Context for global data that many components need to access, but not for every piece of state.


### Creating & Providing The Context

Learned how to create and provide context in a React application. Best practice involves creating a separate file for context and provider to keep the code organized and maintainable.


### Consuming the Context

Understood how to consume context using the `useContext` hook. Best practice is to use context sparingly to avoid performance issues, and to structure context in a way that minimizes re-renders.


### Linking the Context to State

Learned how to link context to state and update context values based on state changes. Best practice is to keep state and context separate when possible, and to use reducers for complex state logic.


### A Different Way Of Consuming Context

Explored alternative ways of consuming context, such as using custom hooks. Best practice involves creating custom hooks that encapsulate context logic to keep components clean and focused on UI logic.


### What Happens When Context Values Change?

Understood the implications of context value changes on component re-renders. Best practice is to memoize context values and avoid unnecessary updates to optimize performance.


### Migrating the Entire Demo Project to use the Context API

Migrated the entire project to use the Context API. Best practice is to refactor incrementally and ensure that context logic is well-tested to prevent bugs during migration.


### Outsourcing Context & State Into a Custom Hook

Learned how to outsource context and state management into a custom hook. Best practice involves creating hooks that handle specific logic, making the code modular and easier to maintain.


### Introducing the useReducer Hook

Got introduced to the `useReducer` hook for managing complex state logic. Best practice includes using `useReducer` for state that involves multiple sub-values or when the next state depends on the previous one.


### Dispatching Actions & Editing State with useReducer

Learned how to dispatch actions and edit state using the `useReducer` hook. Best practice is to define action types and reducer functions clearly to ensure that state transitions are predictable and maintainable.


    