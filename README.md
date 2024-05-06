# React
React Components

#Destructuring Arrays and Objects
Destructuring is a crucial JavaScript concept that allows dynamic retrieval of properties from the props object in the app.js file, enhancing clarity and allowing direct property extraction by their keys.
Array destructuring is a destructuring technique used to assign names to values in an array, allowing for the extraction of specific values like "Tokyo" or "Tahoe City" without assigning variable names based on keys.

The useState Hook
The useState function in React applications is a crucial method for managing state variables. It retrieves an array with an undefined value and a function, which updates the initial state when the app is refreshed.
The initial state of an application is set by passing a value to useState, which can be changed by calling setEmotion with a new state. This dynamic state management allows for the display of emotions like 'happy','sad', and 'excited', ensuring the app's state remains constant throughout the application.

Working with useEffect
UseEffect is a useful tool in React for handling non-returning components like console messages, loading data, or animations. It imports from React and can be used in a component like a console log. The function takes two arguments: the function for the effect and the dependency array that decides when the effect should be applied. The dependency array can be one-time or listen for changes in a variable.

The Dependency Array
UseEffect and useState calls manage variables, including secondary variable "emotion" with initial state "tired". UseEffect triggers changes in primary emotion, while dependency array tracks changes. Include specific state variables for useEffect to trigger on changes.

Using the useReducer
The useEffect call is being replaced with a checkbox that integrates with useState, simplifying state management. The checkbox will be a type of checkbox with a label, and a variable called "checked" and its partner "setChecked" will be created, starting with a false status.

The "checked" variable is responsible for the checkbox state, so manipulating it can shake things up. OnChange will serenade setChecked, returning its alter ego. The label will echo this change, initially false. Toggle checked to toggle the state.

The text suggests outsourcing state updates to a separate function, like useReducer, instead of juggling it inside onChange. This allows for a consistent state update and initial state, ensuring that the output remains cool and avoids bugs by avoiding extra onChange code.

React Forms
Working with Uncontrolled Components
In a React project, handling form inputs is crucial. The useRef hook allows access to individual elements like text and color inputs, allowing us to retrieve their values using current. This allows us to create an uncontrolled component without triggering re-render.

Creating Controlled Form Elements
Forms can be managed using state, transitioning from uncontrolled to controlled components. By removing useRef, setting up state variables, and using onChange events, forms become controlled components, directly interacting with input values.

Building a Custom Hook
React hooks enable the creation of custom hooks for various functionalities, simplifying form structures and enabling user input management. Hooks are like tools in a toolbox, ready for efficient and clean code across projects.

Choosing a Form Library
Formik and React Hook Form are excellent form libraries for comprehensive management and advanced TypeScript support, respectively. Usehooks.com offers resources for creating various hooks, streamlining form-related tasks and allowing users to choose tools best suited to their project needs.

Asynchronous React
Fetching Data with Hooks
To use React to retrieve live data from the GitHub API, use the useState and useEffect hooks. Create a container for data, initialize state with 'null', and use useEffect to fetch data for a user. Handle response with '.JSON' method. Display data in pre-formatted tag.

Displaying Data from an API
Create a 'GithubUser' component with H1 name, location, and image, using React's property passing mechanism for flexible data displays.

Handling Loading States
Use useState to manage loading states for external API calls, setting them with updating functions. Adjust component rendering logic based on these states, showing loading, success, and error messages accordingly.

Fetching Data with GraphQL
Adapt data fetching capabilities to GraphQL APIs by specifying endpoints and queries, ensuring correct data structure, and adjusting code for nested data structures.

Working with Render Props
A flexible pattern is used to render lists using functions. This pattern includes a 'List' function, which takes in data, renders individual items, and renders when the list is empty, ensuring dynamic rendering based on the provided data.

React Routers
Configuring the Router
Use useState to manage loading states for external API calls, setting them with updating functions. Adjust component rendering logic based on these states, showing loading, success, and error messages accordingly.

Incorporating the Link Component
The 'Link' component from React Router can be integrated into the Home component to create links to other pages, enhancing user-friendly navigation. Importing this component into the Home component ensures seamless access to desired pages.

Nesting links with React Router v6
To add a child page to the About component, create 'Our History' and nest a new Route inside the About Route for '/history'. Import the History component into your app file and place 'Outlet' in App.js. Nested routes structure your app effectively, but plan your route configuration first.

React Deployment
Running Tests with Create React App
Create React App offers 'npm test' for executing all tests in the app, allowing for identification of failed tests and potential code issues, and will discuss writing and linking tests to app functions.

Testing Functions with Jest
To test small functions using Jest, create 'functions.js' for code and 'functions.test.js' for tests. Jest is configured in Create React App, allowing for easy testing of functions like 'timesTwo', ensuring robust code.

Using React Testing Library
The React Testing Library is a useful tool in Create React App, automating the testing process by checking if a component contains the expected content, simplifying the testing workflow.

Testing Events with React Testing Library
We'll create a 'Checkbox' component and test file using React's 'useReducer' to simulate events, catch errors, and identify potential issues in our code.

Deploying to Netlify
Netlify simplifies the deployment of our React app by generating a build folder, deploying the project, and enabling easy customization. Its user-friendly interface allows for setting up a custom domain or enabling HTTPS support, making the process quick and enjoyable.
