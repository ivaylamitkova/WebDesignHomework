This is my assignment 4 folder.
1. Explain how web browsers function. -
   This is the basic flow of viewing a web page.\ Send a request over the net to a server.\ It responds with a collection of web content as a response.\ Your browser interprets the content and displays the page.\
   The components of a browser:
   1. User Interface - This is what is presented to the user to interact with. It displays the address bar, back and forward buttons, and any other visual elements that you can interact with such as tabs.
   2. Rendering Engine -  Responsible for displaying the visual representation of the web page. It is like a painter painting on a blank canvas. It has the responsibility of constructing the page by applying the right structure and colors. It takes in HTML and CSS documents and displays its interpretations of both.
   3. Browser Engine - Acts like a marshall and directs actions between the user interface and the rendering engine as well as external communication with servers.
   4. Network - Needs this in order to communicate.
   5. JavaScript - To apply interactive logic and functionality we use a programming language called javascript. But we need a way to translate the communication between JavaScript and the web.
   6. JavaScript Interpreter - Each browser has its own JavaScript interpreters.
   7. Data Storage - Cookies and Local Storage - helps to retain state even when you refresh the page. Cookies remember bits of information.
      Not all browsers use the same rendering engine. This is why we see inconsistencies in how things look from browser to browser.
      First, the rendering engine reads the HD amount and constructs a DOM (Document Object Model). All the CSS styling associated with these notes is passed by the engine. A new tree is created and it goes through a layout process where each node is put on the screen with coordinates. UI Backend Layer does the painting. The process happens so fast. When the passing process has finished then the browser will mark the document as interacting, allowing everyone to interact and access it.
2. Define and describe DOM? - Document Object Model - Interface to a document and stipulates how a document is accessed and changed by defining its structure in a logical way. The DOM represents these documents as nodes and objects on a tree structure so that programming languages such as JavaScript can modify the content.
3. What is the difference between HTML XML and XHTML?
   HTML or HTM stands for Hypertext Markup Language - It is the first and most well-known of internet languages. Functions as the foundation and structure of a page's content. After it is set, other aspects can be embedded or attached to that page, like stylesheets or scripts. Does not have consistent version changes and updates require extended education. The quality of HTML usage is varied, meaning that sites may not always work cross-browser or cross-device.
   XML stands for Extensible Markup Language and it is a compliment to HTML because XML describes document nodes, whereas HTML displays document nodes. It does not "do" or render anything, just provides tagged information and there are no pre-defined tags, the author must define and structure them individually.
   XHTML stands for Extensible Hypertext Markup Language and it is a bridge between HTML and XML. It combines the best of both in an attempt to correct some lenient behaviors of HTML; in particular, those that cause problems on mobile devices. While computer browsers can correct some "bad" HTML, smaller devices often lack the resources to perform these operations. It is more precise therefore it is more time-consuming to write.
4. What are the 4 elements your HTML pages need?
   1. The <!DOCTYPE> declaration - should be placed on the first line
   2. The <root> element - 
   3. The <head> element
   4. The <body> element
5. What is the index.html page for? Where does it go? - There can be multiple index files on a site, but at least one index is the homepage of this site.
6. Review. What are some of the best naming practices? - Organizing files is important for web development because a URL contains paths, which effectively provide directions to your files. To make it easy for you to update and make changes to the website, your pages folder might have pages that have their own unique name. All of the pages will stay in the pages folder. E.g. page1.html, page2.html, page3.html, etc. You can use a sitemap to help you visualize the setup.
   
