# Lab 6 - Node.js and Pystache
#### In this lab, I explored server-side JavaScript using Node.js along with Python-based templating using the Pystache library. The goal was to understand how web servers can be created and run using Node, how they handle incoming requests, and how they respond with data. I also learned how to use Pystache for simple text-based templating in Python, simulating dynamic content generation. Through a combination of scripts and terminal-based tests, this lab provided hands-on experience with lightweight back-end web development and template rendering.

## Install Node.js and run hello-world.js, hello.js, and http.js
### hello-world.js
#### This script sets up a basic Node.js HTTP server that listens on port 3000. When accessed, it displays a simple message confirming that the server is running. It demonstrates the foundational structure of a Node.js web server.
![alt text](hello-world.jpg)
![alt text](hello-world-output.jpg)

### hello-world.js
#### This file extends the functionality of the previous script by responding to incoming HTTP requests. When the server is accessed via a browser at http://127.0.0.1:8080, it outputs a message like “Hello, World!” and logs server activity to the terminal, allowing real-time interaction and monitoring.
![alt text](hello.jpg)
![alt text](hello-output.jpg)

### hello-world.js
#### The http.js script showcases how a Node.js server can output numbers to the browser using a loop. It writes multiple lines of output directly to the HTTP response and then closes the connection. This example emphasizes how server-side logic can dynamically control what is served to a client.
![alt text](http.jpg)
![alt text](http-output.jpg)

## Install Pystache and run say_hello.py
### say_hello.py
#### This Python script uses the pystache library (a Mustache templating engine for Python) to render templates. It demonstrates:
#### - Simple placeholder replacement (e.g., {{person}})
#### - Rendering from a class object (SayHello)
#### - Parsing and reusing a Mustache template for dynamic input ("Google", "Siri")
#### This section introduces logic-less templating in Python and how data can be inserted into HTML-like templates for flexible content generation.
![alt text](say_hello.jpg)

#### By completing this lab, I gained practical experience with both Node.js and Pystache. Running scripts like hello-world.js, hello.js, and http.js demonstrated how simple servers are created and managed using Node, while say_hello.py showed how templating works in Python with Pystache. These tools are foundational in web and IoT development, and this lab helped reinforce how server-client communication and template-driven output can be structured in real-world applications.
