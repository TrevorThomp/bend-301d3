## Read 01: Responsive Web Design

Responsive web design is the approach of building a website that is able to be used on every device and screen size. It's focus is to be responsive for any viewport and for the overall experience of the website to be very similar no matter what device you are using. Typically, those who approach a responsive design will develop the website from a "mobile-first approach", which means you develop the site for smaller devices first, then as the viewport re-sizes you make the necessary adjustments.

### Flexible Layouts

Responsive websites are typically developed using flexible layouts, media queries and flexible media. Instead of using fixed measurements when defining placement of elements, you want to have either relative or flexible units such as percentages. This will help to make things more fluid as the viewport changes on different devices. Media queries are also very useful, especially from a mobile-first approach. They allow you to make certain adjustments when the screen size is at a particular width so that certain "breaks" are made on elements and they can align according to the new viewport.

## Read 02: jQuery

jQuery is a JavaScript file that you include in your web pages. jQuery allows you to easily manipulate the dom by targeting CSS selectors and applying methods to those elements. jQuery is initialized by "$" before the given CSS selector. The first parameter when using the jQuery function is always going to be a CSS selector targeting the elements you are looking to target. Once you have defined your targeted element/elements, you are then able to add jQuery methods that will update the targeted element you defined within the parameter.

### Why jQuery?

Everything that jQuery does is able to be done with pure vanilla JavaScript. However, jQuery allows you to complete such tasks with fewer lines of code, and less complexity. jQuery is also accepted in most browsers and is easy to read and maintain. In conclusion, jQuery once you learn the basic selection and methods, can make your JavaScript easy to maintain and you are able to create responsive applications faster.

## Read 03: Flexbox

Flexbox is a one-dimensional layout method for organizing items into rows and columns. Before Flexbox, the main ways to position was positioning and floats. These are still perfectly fine to use but can be frustrating at times when the web page consists of a lot of elements. Flexbox was introduced to make things organized and understandable, it also helps layout containers and the individual items within those containers.

### Flexbox Layout

With Flexbox, you are able to layout major containers on the page with specific properties for those flex-containers. You are also able to target the items individually within those containers with certain flex-item properties. When you set the display:flex on an element, that element becomes a flex-container. All items nested within that element become flex-items and are children of that container. Being able to distinguish the difference between the flex-containers and flex-items are key and will save you a lot of frustration when you are using Flexbox on a web page.

## Read 04: Regex Tutorial

A regular expression(regex) is a sequence of characters that are used to define a search pattern. These search patterns can be used for string algorithms that are sorting through specific criteria. They are also used for input validation such as passwords and usernames. Regex is very useful, especially because it can be used in almost all programming languages.

### Regex Explantions

Regex have many different approaches for scraping data from strings and input. These are done by a multitude of topics. You have your anchors which are ways you can match any string that starts or ends with certain characters. Quantifiers are used to match strings that are followed by either a certain character or number. Flags are used to sort through more of the string with whatever topics you assign to that flag. This can minimize your regular expression to make it more readable. There are many different approaches to regex, I look forward to learning more about them!

## Read 05: Heroku

Heroku is a container-based cloud Platform as a Service (PaaS). Heroku is used to deploy, manage and scale modern applications. Heroku also has a variety of methods to connect to databases such as mySQL and PostgreSQL. Heroku is similar to what we receive when we use live-server to see our projects being updated in real time locally. Heroku allows you to deploy your application locally, and also online through their free dyno system.

As a new user to Heroku, you are allowed to deploy your applications for up to a month on their dyno system as long as it is being used. If the application is not visited for a certain period of time, then the dyno will stop running. As I mentioned earlier, Heroku offers a variety of tools that are their to enhance developer productivity when developing applications.

## Read 06: Node.js

### What is Node.js?

Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient.

Node.js also as great ES6 support so it makes creating applications easier with using the modern syntax. This helps prevent compatibility issues when writing JavaScript for different browsers.

npm is a package manager that gets bundled with Node.js. This a package manager for Javascript, but it's also the world's largest software registry. It currently has over 600,000 packages of JavaScript code available to download.

## Read 07: APIs continued

### What is A REST API?

An API is an application programming interface. It is a set of rules that allow programs to talk to each other. The developer creates the API on the server and allows the client to talk to it.

REST determines how the API looks like. It stands for "Representational State Transfer". REST is a set of rules that developers follow when they create their API. One of these rules states that you should be able to get a piece of data when you link to a specific URL.

## Read 08: SQL

SQL stands for Structured Query Language. SQL is used to communicate with a database. SQL statements are used to perform tasks on databases such as, retrieving data or updating data. There many different statements that SQL can use to do such tasks, but the standard commands: "Select", "Insert", "Update", "Delete", "Create", and "Drop" can typically be used to accomplish most tasks.

SQL databases contain objects that are referred to as tables. These tables are uniquely identified by their names and are comprised of columns and rows. The columns contain the column name, data type, and other attributes. The rows contain the records or data for the columns.

## Read 09: Functional Programming

Functional Programming is very interesting and the logic it uses to emphasize it's importance makes a lot of sense! Functional programming is the paradigm of building functions that don't have mutable data and change state globally. This can be achieved through Pure Functions. These functions don't access global variables to manipulate their data. Instead, these functions take parameters that will only be used in the function especially if the data is being mutated. This is what helps with not mutating global objects that you are using for other functions.

Functional programming also focuses on no side effects. One function should not have a major side effect effecting a lot of other functions throughout your application. You are able to pass functions as arguments, but you shouldn't have multiple functions that are relying on global objects to receive their data. This is what can cause a chain of bugs throughout code that is a mess to debug.

## Read 10: Call Stack

A call stack is a mechanism for an interpreter to keep track of its current place in a script that invokes multiple functions. This stack keeps track of what functions have been invoked and whether or not it moves on to the next function in the stack. Call stacks are single-threaded meaning that they can only do one thing at a time and their code execution is synchronous. It's important to understand the call stack because it's heavily relied on when it comes to Asynchronous JavaScript when we are invoking multiple functions at once throughout the script. 

Although we haven't got into recursion yet, but I'm sure we will in 401. Recursive functions that don't have exit points will cause a stack overflow. It's very similar to a while loop that doesn't have any false conditions and it will cause an infinite loop. A stack overflow error will at least throw an error once it realizes that the call stack has exceeded the memory that should have been allocated to that particular function.