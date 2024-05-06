# React
React Elements
React uses JavaScript to create elements, like a div with ID "root". To render, add a script tag with type "text/javascript" and use "ReactDOM.render" with two arguments: "React.createElement" and "getting started with React."

Creating React Elements
The ReactDOM.render function is used to incorporate the createElement call from line 19 into the document at the 'root' element, infusing React code into it. This allows for viewing elements as UI components that can be rendered whenever needed. The 'Getting Started with React' text is adjusted to test the function's functionality.

Refactoring elements using JSX
To create a bulleted list in React, use React.createElement and modify the third argument to add list items. Start with a list item and add more days. As the UI becomes more complex, use JSX, a JavaScript superhero helper, to create a cool emoji list. However, React does not work with JSX tags, so use Babel to fix this issue.

Incorporating Babel
The text suggests using babeljs.io to convert JSX code into a browser-friendly format. This is achieved by using a CDN link and adjusting the 'text/javascript' to 'text/babel' to fix syntax errors. Babel is a powerful tool for converting complex code into a more user-friendly format, and it is not the most optimized solution. Further tools will be discussed in the future.

JSX Syntax
JSX is a powerful tool for incorporating dynamic content into your apps. It allows you to reference variables with variable names, like "robot" for a robot, "cowboy" for a cowboy, and "moon" for a friendly moon. These values are displayed in list items using curly braces. JSX expressions with curly braces can be incorporated with various functions, such as "toUpperCase()" or "name.length".

React Components
Building React Components involves creating a small, user interface piece. Begin by removing emojis and implementing an unordered list. Next, create a JavaScript function that executes JSX.

 Component Properties
The text outlines the use of components to showcase live data in a restaurant. The components are introduced as props, which can be inserted into the header function. The console.log() function is used to preview the properties, and the name of the component is filled in with the desired name. The main component can also be showcasing delicious food, with the adjective "adjective" added for style. A new property for the footer component is introduced, which returns a footer tag with a copyright year from props. The current year can be added using curly braces. The props object is viewed as a container for storing component information, and dot notation is used for dynamism.

Lists
We have used JSX expressions to send data to components, including strings, date functions, and booleans. However, we now need to handle more intricate data types like arrays. For example, we can map over an unordered list of dishes using dishes.map, which returns a list item for each dish. We can access these values through props, but a console warning is needed for each child in a list.

Applying Keys to List Items
The text discusses dynamically rendering menu items, highlighting the need for unique keys to prevent synchronization issues. Two approaches are discussed: adding an index (i) as a key for each item, which is a potential rendering issue, and creating an array of unique IDs for each dish, which ensures data stability. The importance of keys is emphasized during dynamic value iteration.

React Fragments
Enclosing sibling components in a div prevents errors when wrapping JSX elements. Avoid cluttering setups with div wrappers. Use React Fragment instead, adding React.Fragment with React.Fragment to neatly frame header, section, and footer components. Shorter syntax requires specific React versions.

React State
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
