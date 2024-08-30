

# _Episode 01 - Inception_

## Theory :

- What is `Emmet`?
Emmet is a plugin/tool designed to enhance productivity for web developers by providing a faster way to write HTML and CSS code. Originally known as Zen Coding, Emmet allows developers to write complex HTML structures and CSS rules using shorthand syntax, which it then expands into fully-fledged code snippets. This tool is widely supported by various code editors, including Visual Studio Code, Sublime Text, Atom, and others.


- What is `CDN`? 

A CDN, or Content Delivery Network, is a system of distributed servers located across various geographical locations. The primary purpose of a CDN is to deliver content—such as images, videos, JavaScript files, CSS files, and other web assets—to users more quickly and efficiently.

Why do we `use` it?
Speed Up Content Delivery: CDNs deliver content faster by using servers located closer to the user.
Improve Website Performance: By reducing the load on the main server and distributing it across multiple locations.
Enhance Reliability: If one server fails, another can take over, keeping the website online.
Save Bandwidth: By caching content, CDNs reduce the amount of data sent directly from the main server.
Increase Security: CDNs provide protection against attacks like DDoS and offer security features like SSL encryption.


- Why is `React known as React`?
**React** is called "React" because it **reacts** to changes in data. When the data in a React application changes, React automatically updates the user interface (UI) to reflect those changes. This makes building interactive and dynamic web applications easier, as React handles the updates for you. The name highlights its main feature of making the UI respond quickly and efficiently to changes in the underlying data.

- What is `crossorigin in script tag`?

Security and Error Reporting: It helps manage security and allows the browser to show errors if something goes wrong with the script.
With or Without Credentials: It can specify whether or not to include credentials like cookies when loading the script.
Common Settings:
anonymous: Load the script without sending cookies or other sensitive information.
use-credentials: Load the script and send credentials (like cookies) with the request.


- What is difference between `React and ReactDOM`?
React: This is the core library used for building user interfaces. It lets you create and define components (like buttons, forms, etc.) and manage how they behave and look.

ReactDOM: This is the tool that takes those React components and actually displays them on the web page. It connects React components to the real DOM (Document Object Model) in the browser.

Key Difference:
React is used to build the components.
ReactDOM is used to show those components on the web page.


- What is difference between `react.development.js` and `react.production.js` files via CDN?
react.development.js:
For Developers: Used during development to help catch errors and debug.
Includes Warnings: Has helpful error messages and warnings.
Not Minified: Bigger file size, easier to read.
react.production.js:
For Live Websites: Used when the app is ready to go live.
No Warnings: Removes extra error messages to make the app faster.
Minified: Smaller file size, optimized for speed.
Key Difference:
Development: react.development.js is for building and debugging.
Production: react.production.js is for when your app is finished and needs to run quickly on a live site.



## Coding :

- Set up all the `tools in your laptop`
  - `VS Code`
  - `Chrome`
  - `Extensions of Chrome`
- Create a `new Git repo`
- Build your `first Hello World` program using,
  - Using `just HTML`
  - Using `JS to manipulate the DOM`
  - Using `React`
    - use `CDN Links`
    - Create `an Element`
    - Create `nested React Elements`
    - Use `root.render`
- `Push code to Github` (Theory as well as code)
- Learn about `Arrow Functions` before the next class

## References:

- https://beta.reactjs.org/apis/react/createElement
- https://www.youtube.com/watch?v=IrHmpdORLu8
