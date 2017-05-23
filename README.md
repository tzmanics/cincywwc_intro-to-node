# Intro to Node
## Info
### What is Node?
A JavaScript environment built on V8, which is the same JavaScript engine that Chrome uses.  Node is considered JavaScript on the server-side.

Node uses an event-driven, non-blocking I/O model. 
![event-driven](https://www.tutorialspoint.com/nodejs/images/event_loop.jpg)
This means as soon as we start the Node server it initiates its variables, declares functions and waits for an event to occur. The event loop listens for events then triggers a callback function when an event is detected.

This tends to make performance with Node more attractive than other server-side languages like PHP and Ruby on Rails.

Node's package manager, npm, is the largest ecosystem of open source libraries in the world.

// Although events look quite similar to callbacks, the difference lies in the fact that callback functions are called when an asynchronous function returns its result, whereas event handling works on the observer pattern. The functions that listen to events act as Observers. Whenever an event gets fired, its listener function starts executing. Node.js has multiple in-built events available through events module and EventEmitter class which are used to bind events and event-listeners


### What do you use Node for?
Node is great for creating server-side application middle tiers like web services for API's and web servers. Is often used as the runtime for the backend of a web application. If you use a JavaScript framework like Angular, React, Vue, Aurelia, etc. you can share some of your code and modules between back and front-end. This is considered Isomorphic JavaScript, which also means besides sharing code you can also take advantage of universal rendering (building views of your app server-side), universal routing (know the view associated to the current route from the server and the browser) and universal data retrieval (accessing data from the server and browser (usually using an API)).


### Who uses Node?
NASA, Adobe, Google, Microsoft, Netflix, PayPal, Uber, Walmart and a ton more!
![node users](https://intesso.github.io/nodejs-introduction/img/used-by.png)

### How do you use Node with your front-end?
[Scotch.io Universal React on Node](https://scotch.io/tutorials/react-on-the-server-for-beginners-build-a-universal-react-and-node-app)
[Adrian Mejia Angular with Node](http://adrianmejia.com/blog/2014/09/28/angularjs-tutorial-for-beginners-with-nodejs-expressjs-and-mongodb/)
[Connor Leech app with Vue and Node](https://medium.com/@connorleech/building-a-feature-complete-bookmarking-app-with-vue-js-express-and-sequelize-orm-b36506ebcb4c)
[Dwayne Charrington Aurelia Starter Node Skeleton](https://ilikekillnerds.com/2016/02/aurelia-starter-node-skeleton/)

## Workshop/Demo

### Install Node 
  Installed with npm and nvm included, 

[https://nodejs.org/en/download/](https://nodejs.org/en/download/)

### Create a Repo and a Project
`mkdir <project name> && cd <project name>
`git init`
`npm init`

Run your brand new project
`node index.js`
check it by curling your localhost port 3000
`curl localhost:3000`


### Using Express
Express is a light-weight web application framework to help organize your web application into an MVC architecture on the server side.

`npm install express --save`

