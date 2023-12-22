# Simple HTTP Server in Go

This project is a simple HTTP server written in Go. It has three main endpoints:

1. **Root Endpoint ("/")**: Serves static files from the `./static` directory. The main file served is `index.html`.

2. **Hello Endpoint ("/hello")**: Accepts only GET requests and prints "Hello!" to the console.

3. **Form Endpoint ("/form")**: Handles form data. It parses the form data from the request and prints a success message along with the form values for "name" and "address".

The server listens on port 8080. If there's an error while starting the server, it logs the error and terminates the program.