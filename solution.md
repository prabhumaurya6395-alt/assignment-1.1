1. Explanatory Paragraph
When we type a URL (website address) into a web browser like Google Chrome, the browser acts as a client and sends a request to the web server using HTTP or HTTPS. First, the browser finds the IP address of the website using DNS. Then, it sends an HTTP request to the server. The server receives the request, processes it, and may communicate with a database to get the required information. After processing, the server sends an HTTP response containing HTML, CSS, JavaScript, images, and other files back to the browser. The browser reads these files and displays the website on the screen. This process is called the request-response cycle. HTTP stands for HyperText Transfer Protocol, which is used to transfer data between a browser and a server. HTTPS stands for HyperText Transfer Protocol Secure, which provides a secure and encrypted connection. A static website displays fixed content that usually remains the same for every visitor, while a dynamic website displays changing content based on user actions, database information, or other conditions. For example, a simple portfolio website can be static, while Facebook and Amazon are dynamic websites.

2. Basic Roles
Term

Meaning

Browser

Software used to open and view websites, such as Chrome.

Client

The user's device or application that sends requests to a server.

Server

A computer that receives requests and sends website data.

Database

Stores and manages website information, such as user accounts and products.

3. HTTP and HTTPS
HTTP: HyperText Transfer Protocol. It transfers information between a browser and a web server.

HTTPS: HyperText Transfer Protocol Secure. It transfers information securely using encryption.

4. Request-Response Cycle
1. Client / Browser

User enters a website URL

2. HTTP Request

Browser sends a request to the server

3. Server and Database

Server processes the request and retrieves data if needed

4. HTTP Response

Server sends the requested files and data

5. Website Displayed

Browser displays the website on the screen

5. Difference Between Static and Dynamic Websites
Static Website

Dynamic Website

Displays fixed content.

Displays changing content.

Usually uses HTML and CSS.

Uses HTML, CSS, JavaScript and often a backend.

Content is generally the same for all visitors.

Content can change based on users and data.

Usually does not require a database.

Often uses a database.

Example: Simple portfolio website.

Example: Facebook, Amazon.

6. Chrome DevTools — Network Tab
You need to perform this practical activity yourself and attach its screenshot.

Front End Debugging Part 3: Networking
 
Steps to take your screenshot:

Open Google Chrome.

Visit https://www.google.com.

Press F12 on your keyboard.

Click the Network tab.

Refresh the website using Ctrl + R.

Wait for the requests to load.

Take a screenshot showing the Network tab and its requests.

Attach the screenshot below your assignment.

What you can observe in the Network tab:

Name: Name of the requested file.

Status: Response status code (200 means successful).

Type: Type of resource, such as document, script, or image.

Size: Size of the transferred file.

Time: Time taken to complete the request.

Waterfall: Visual representation of request loading time.