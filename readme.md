How Web Works Exercise
======================

Part One: Solidify Terminology
------------------------------

In your own terms, define the following terms:

*   What is HTTP?  

  HTTP is HyperText Transfer Protocol, and is a set of rules and standards for the connections we make on the web

*   What is a URL?  

A URL is an address with different components to instruct where we want to go, what we want to get from there, and how we want to go  

*   What is DNS?  

A DNS  (Domain Name Service) is what turns a hostname into an IP address.

*   What is a query string?  

A query string is a string that appears at the end of a request (usually a GET) request, which gives the server additional information about what it is that we're looking for

*   What are two HTTP verbs and how are they different?  

GET is an HTTP method that does not generate side effects, whereas POST is a method that does generate side effects and expects to change data

*   What is an HTTP request?  

An HTTP request is a message sent to a server with details about what it wants to be sent back

*   What is an HTTP response?  

An HTTP resposne is what comes back from the server in response to the request

*   What is an HTTP header? Give a couple examples of request andresponse headers you have seen.  

HTTP headers contain data about the request, such as where it came from, what language it would like to see results in, what format it expects results to be in, etc.

*   What are the processes that happen when you type“[http://somesite.com/some/page.html](http://somesite.com/some/page.html)” into a browser?  

My computer checks to see if it knows what the IP address is for that site, then if it does not know, checks with the ISP and then eventually the DNS server, then when it has the IP address, it sends that request to the IP address. The server gets the request and responds with the requested resource. If there are additional resources that the page needs, after my computer receives the page back it will then repeat this process for those needed resources, and alter the contents of my page as those responses come back.


Part Two: Practice Tools
------------------------

1.  Using curl, make a GET request to the _icanhazdadjoke.com_ API to findall jokes involving the word “pirate”
2.  Use dig to find what the IP address is for _icanhazdadjoke.com_
3.  Make a simple web page and serve it using python3 -m http.server.Visit the page in a browser.

Part Three: Explore Dev Tools
-----------------------------

Build a very simple HTML form that usesthe GET method (it can use the same page URL for the action) when the form is submitted.

Add a field or two to the form and, after submitting it, explore in ChromeDeveloper tools how you can view the request and response headers.

Edit the page to change the form type to POST, refresh in the browserand re-submit. Do you still see the field in the query string?Explore in Chrome how you can view the request and response headers,as well as the form data.

Part Four: Explore the URL API
------------------------------

At times, it’s useful for your JavaScript to look at the URLof the browser window and change how the script works dependingon parts of that (particularly the query string).

[Read about the URL API](https://developer.mozilla.org/en-US/docs/Web/API/URL)

Try some of the code examples in the Chrome Console so that you can get comfortable with the basic methods and properties for instances of the URL class.

Solution
--------

You can [view our solution](solution/index.html)