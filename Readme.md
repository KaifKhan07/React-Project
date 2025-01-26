# ***    React JS Notes    ***

# First Program in React 
=>
* React & ReactDOM is Very important in React JS APP...

const heading = React.createElement("h1", {}, "Hello World");   // React Used 
        
const root = ReactDOM.createRoot(document.getElementById('root'));    // ReactDOM to Print on UI...
root.render(heading);

# What is diference between React and ReactDOM?
=> 
React: The core library for building components, managing state, and creating the virtual DOM.
ReactDOM: The library responsible for rendering React components to the actual DOM in the browser.
Think of React as the "brains" and ReactDOM as the "hands" that interact with the browser.

# Difference Between react.development.js and react.production.js?
=>
* react.development.js:

- Used during development.
- Includes helpful warnings, error messages, and debugging tools.
- Larger file size and slower performance.

* react.production.js:

- Used in production (live environments).
- Stripped of warnings and debugging tools.
- Smaller file size and optimized for performance.
- Key Takeaway: Use react.development.js for debugging and react.production.js for deployment.


# What is async and defer?
=> 
async and defer (Attributes for <script>):

* async:

- Downloads the script in the background and executes it as soon as it's ready.
- May block rendering if the script finishes downloading early.

* defer:

- Downloads the script in the background but waits to execute it until the HTML is fully parsed.
- Ensures scripts run in order.

* Key Difference:
- Use async for independent scripts (e.g., analytics).
Use defer for scripts that depend on or affect the HTML structure.



