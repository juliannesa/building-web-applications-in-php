Notes
============================================================================================================================================

Tecnology is made by people

Php makes things more dynamic, better than writing web code with C. 
https://www.youtube.com/watch?v=YIGRXEzjE6c

SQL was an abstraction made by a lot of companies to create a database pattern
https://www.youtube.com/watch?v=rLUm3vst87g

JavaScript talks to the browsers through this thing called the DOM, document object model, which is not standardized like the rest of JavaScript.
DOM is the thing that JavaScript does to change what's going on in the browser. So,  jQuerry solved it, being a portability layer. 

JSON, JavaScript object notation, is basically the format of data that talk to the server on your behalf, sending things without even you doing anything.
Like, go check to see if there's any new messages. Go check to see if there's any new messages. Well the new messages come back in a format called JSON. 
It was actually part of JavaScript, a protocol that then capture or captured that and then we use that for a lot of different things. 

how web applications work
In a web browser, you've got the browser and then you've got the server and then you've got a database server.

Request response cycle
the browser is talking to the server and we're writing code in the server to respond, and what goes back and forth
and that's HTTP, Hyper Text Transport Protocol
predate HTTP like FTP for file transfer, Telnet, SMTP for simple mail transfer

Uniform Resource Locator
https://  |  www.google.com  | index.htm   |   ? x = 
protocol  |   host           |   document  |    can be used to be sure that is the most updated page, not a cached one

htm is the same as html, but html is older way to use it

 <a> Anchor tags are clickable links that have an href, a Hyper Text Reference
 href = when someone clicks on this link, throw this page away and go to a different page
 the clink turns into a GET request which retrieves a page which gives us back new HTML which, then is shown in our browser. 

The client view the web using a BROWSER, a software downloaded on the device
Browser comunicates when it receives a command such as a click  to the web server using the port 80 sending a request using HTTP
The response comes in HTML, and the browser parse/render it, using DOM.

The Internet Standarts is all defined bt IETF.
https://www.ietf.org/
HTML and CSS Standarts is defined by W3C, World Wide Web Consortium
https://www.w3.org/

Developer Mode enabled so you can examine the HTTP Response headers
Inspect -> Network
it can be seen using telnet, a different protocol TCP/IP used to establish a connection with a remote pc
telnet [hostname/ipaddress] [port number]
This command allows you to troubleshoot and test various services on a server.
One of the main uses of the telnet command is to check if a given port is listening on a server.
The response can be parsed in two parts: HEAD, BODY.
HEAD = metadata
BODY = the content-type described in the head

HTTP Response Code
 200 code indicating a normal document retrieval
 304 code means that your browser is likely using a cached copy of the file
 404 code = not found
more https://en.wikipedia.org/wiki/List_of_HTTP_status_codes

QUIZ
============================================================================================================================================
Reminder to whom it may concern: When they block copy/paste function on the website, you can inspect it and copy from the code

1) When a browser connects to a web server to retrieve a document, what is the default TCP/IP port that is used? 80
2) When a browser connects to a web server to retrieve a document, what command is sent to the server? GET
3) Which of the HTTP headers does the browser look at to decide how to display the retrieved document? Content-Type
4) What does the second "T" of HTTP stand for? Transfer
5) Which of the following is NOT part of a Uniform Resource Locator? Operation System
6) Which HTML tags typically generate a request to retrieve a document? a / img
7) What standards organization publishes many of the documents that describe the protocols we use on the Internet? IETF
