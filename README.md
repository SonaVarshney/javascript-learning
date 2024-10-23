# Javascript Notes

## What is JavaScript?

**Definition:** JavaScript (JS) is a high-level, interpreted programming language used for adding interactivity and dynamic behavior to websites.

## What Does It Do?

- **Interactivity:** Enables interactive elements like buttons, forms, and animations.
- **Dynamic Content:** Updates HTML content and CSS styles in real time without reloading the page.
- **Event Handling:** Responds to user actions (e.g., clicks, key presses) to enhance user experience.
- **Data Handling:** Communicates with servers via APIs for fetching and submitting data asynchronously.

## Why is It Needed?

- **Improves User Experience:** Makes web applications engaging and responsive.
- **Versatile Usage:** Utilized in both front-end (browser) and back-end (server) development.
- **Cross-Platform Support:** Works across all modern browsers and platforms, making it essential for web development.

## Execution Context

**Definition:** An execution context is the environment in which JavaScript code is executed, holding information about variable scope and function execution.

### Types of Execution Context

- **Global Execution Context:**

  - The default context where JavaScript starts executing.
  - Corresponds to the global object (window in browsers).

- **Function Execution Context:**
  - Created each time a function is invoked.
  - Maintains its own scope and variables, separate from the global context.

### Components of Execution Context

- **Variable Environment:**

  - Stores variables and function declarations for the current execution context.
  - Ensures variable resolution through the scope chain.

- **Scope Chain:**
  - Allows access to variables from the current context and its parent contexts.
  - Facilitates lexical scoping, where nested functions can access outer variables.

## Thread of Execution

**Definition:** The order in which JavaScript executes code. JavaScript operates in a synchronous single-threaded manner, meaning it executes one command at a time.

### Key Concepts

- **Call Stack:**

  - A data structure that keeps track of execution contexts.
  - A new execution context is pushed onto the stack when a function is called and popped off when the function completes.
  - <img src="https://github.com/user-attachments/assets/9553e094-2241-4dc7-85cb-a2b699d7da76" alt="Alt text" width="300"/>


- **Asynchronous Behavior:**
  - JavaScript can handle asynchronous operations (like API calls) using callbacks, promises, and async/await to prevent blocking the main thread.
