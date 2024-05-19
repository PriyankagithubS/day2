# Document vs window object

In web development, both the document and window objects are fundamental components of the browser's JavaScript environment, but they serve different purposes and have distinct roles. Here’s a detailed comparison between the two:

Window Object: The **window object** represents the browser window or a frame that contains a document. It is the global object in the browser environment.

•	Global Scope: All global JavaScript objects, functions, and variables automatically become members of the window object. For example, window.alert() and simply alert() are the same.

•	Properties and Methods:               
        Browser Interaction: Methods for controlling the browser window, like alert(),confirm(),prompt(),open(),close(),setTimeout(),setInterval(), etc.

        Location: Access to the current URL via window. Location.
        History: Access to the browser's history via window.history.
        Navigator: Information about the browser via window.navigator.
        Screen: Information about the user's screen via window.screen.
•	Event Handling: Global events like resize, scroll, load, and unload are associated with the window object.

•	Document Object: The **document object** is a property of the window object (window.document).

Document Object: The document object represents the HTML or XML document that is loaded into the window. It is a property of the window object.

•	DOM Interface: Provides a way to access and manipulate the content of the web page. It is the root of the Document Object Model (DOM).

•	Properties and Methods:

        Element Selection: Methods like getElementById(),      getElementsByClassName(),getElementsByTagName(),querySelector(), and querySelectorAll().

        Content Manipulation: Methods for creating elements (createElement), adding text (createTextNode), and modifying the DOM (appendChild, removeChild, replaceChild, innerHTML, etc.).

        Document Information: Properties like document.title, document.URL, document.domain, and document.cookie.
•	Event Handling: Handles events specific to the document content like click, keydown, submit, etc.

•	Rendering: The document object is responsible for the rendering of the content within the window. It provides access to the structure and style of the webpage.

 ### DIFFERENCES
 
1. Scope:
   
     •	window is the global scope object and represents the entire browser window.

     •	document is a property of window and represents the content of the webpage.

2. Functionality:
   
     •	window is concerned with the browser window and overall environment.

     •	document is focused on the webpage content and the DOM.

3. Usage:
   
     •	Use window for tasks like opening new browser windows, controlling the current window, accessing global properties and methods, and handling global events.

     •	Use document for manipulating the HTML content, traversing the DOM, handling document-specific events, and accessing information about the webpage.





