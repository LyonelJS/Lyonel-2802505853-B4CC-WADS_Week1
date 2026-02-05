# Student Information
* **Name:** Lyonel Judson Saputra
* **Student ID:** 2802505853
* **Class:** B4CC


# How Node.js Works: A Comprehensive Guide
Node.js is an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside a web browser. It allows developers to use JavaScript to write command-line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser.

### The Architecture
Node.js is built on the V8 JavaScript engine, the same engine that powers Google Chrome. It uses an event-driven, non-blocking I/O model that makes it lightweight and efficient.

![Node.js Architecture](https://nodesource.com/assets/blog/how-nodejs-works/architecture.png)

### The Event Loop
The heart of Node.js is the Event Loop. Unlike traditional web servers that create a new thread for every request, Node.js operates on a single thread, using non-blocking I/O calls. This allows it to support tens of thousands of concurrent connections without incurring the cost of thread context switching.

![The Event Loop](https://nodesource.com/assets/blog/how-nodejs-works/event-loop.png)

### Why Use Node.js?
* **Asynchronous and Event Driven:** All APIs of Node.js library are asynchronous, that is, non-blocking.
* **Very Fast:** Being built on Google Chrome's V8 JavaScript Engine, the library is very fast in code execution.
* **Single Threaded but Highly Scalable:** Node.js uses a single-threaded model with event looping.


---
*Source: [NodeSource - How Node.js Works](https://nodesource.com/blog/how-nodejs-works)*
