## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?

Your browser and OS check the cache to see if they have an IP address for example.com stored. If not, they will contact the DNS to check if example.com. is valid and what its IP address is. The name example.com will be converted to an IP address 192.541.85.0 (or whatever) and your router will send your TCP connection request to your ISP which will connect you (probably through another ISP) to the server which hosts the page you're trying to visit. Once the TCP connection is established, your browser will send an HTTP request to the server. At that point the server will look at the request and send a response, and (hopefully) your browser will display the sweet, sweet HTML content.
 
1.  What does HTTP stand for?

hyper text transfer protocol.

1. 	What protocol does the World Wide Web use?

HTTP and HTTPS

1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?

internet protocol.

1. 	What does DNS stand for?

Domain Name System

1. 	How are text domain names matched to their respective numeric IP addresses.

They are stored on DNS servers which are queried by your computer.

1. 	What is the client?

The software which requests information from a server (browser)

1. 	What does URL stand for?

uniform resource locator.

1. 	What are protocols

The standardised method for transferring data or documents over a network

1. What does DNS stand for?

You already asked this friends.

1. what is the `www` portion of a url?

Host name? It stands for world wide web. But man, you don't even need to type it in anymore!

1. What is The markup language used for all web documents?

HTML

1. What is the organization that monitors web technologies?

W3C. World Wide Web Consortium.

1. What is the Protocol for transferring web documents on the Internet?

Hyper text transfer protocol.

1. What matches the domain names with numeric IP addresses?

DNS resolver.





