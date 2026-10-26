Assignment 1 – What Happens Between Typing a URL and Seeing the Page?

Introduction

When we type a URL into a browser and press Enter, several steps take place before the webpage appears on the screen.

Steps Involved

1. Cache Check: The browser checks its cache for previously stored resources.

2. DNS Lookup: The browser uses DNS to translate the domain name (e.g., example.com) into an IP address.

3. Connection Establishment: The browser establishes a connection with the server. HTTPS connections use TLS to secure communication.

4. HTTP Request: The browser sends an HTTP request, such as "GET /index.html", to the server.

5. Server Response: The server processes the request and sends back a response containing a status code, such as "200 OK", and the requested content.

6. HTML Parsing: The browser parses the HTML document and builds the Document Object Model (DOM).

7. Resource Loading: The browser discovers and requests additional resources such as CSS, JavaScript, images, and fonts.

8. CSSOM and Render Tree: The browser processes CSS to build the CSS Object Model (CSSOM) and combines relevant DOM and CSSOM information to create the render tree.

9. Layout and Painting: The browser calculates the position and size of page elements and paints them on the screen.

10. JavaScript Execution: JavaScript runs as needed and may update the page dynamically.

Conclusion

Displaying a webpage involves communication between the browser and server, followed by parsing, styling, layout, and rendering. These processes work together to display the webpage to the user.