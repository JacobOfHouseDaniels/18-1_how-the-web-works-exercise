- What is HTTP?
HTTP is the Hypertext Transfer Protocol, it is essentially the hostname or resource thereof you request to access a specific website/server. There is important information that is exchanged between your browser and the

- What is a URL?
Uniform Resource Locator, a address used by browsers, servers, and the console to reach a unique resource via the internet or local network.

- What is DNS?
A Domain Name Server translates a human readable address name into one that can be recognized by machine  input to retrieve the correct resource.

- What is a query string?
Additional information tacked on to the end of the URL to produce another page or alter incoming/outgoing data.

- What are two HTTP verbs and how are they different?
GET and Post - Get retrieves information using a request and Post sends information using a request.

- What is an HTTP request?
A HTTP method asking a server for specific data, like a web page. Usually a Get request.

- What is an HTTP response?
The information the server sends back in "response" to the request made, whether that be an HTML page, cookies, cached data, etc.

- What is an HTTP header? Give a couple examples of request and response headers you have seen.
Relevant additional information about the HTTP request method used.

Request Example: Acceptance, Host info, Cookies

Post Example: Last Modified, Content-Type, Set-Cookie



- What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?

1. The browser translates the URL name into an IP address through the DNS.

2. Browser then creates a request to that IP address with the necessary headers included.

3. The IP address' server host will send back a response, usually HTML, with its own headers and status code of the success of the request.

4. The browser takes the response and creates a DOM from the HTML given, searching for all referenced files, such as images, style sheets, and scripts.

5. The browser will create individual HTTP requests for those files and receive a response from each.