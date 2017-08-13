## Website Performance Optimization portfolio project

To get started, check out the repository and inspect the code.

### Getting started


1. Check out the repository
1.  Clone or Download the project code. 

1. Open the project folder on your machine and double click on index.html to view the page on your machine.
1. You can use the Chrome Developer Tools to test the web page code and also view the web pages on phones, tablets and phablets etc.

### Optimizations made in the project


1. Inline CSS styles and asynchronous Java Scripts in index.html, project-2048.html, project-mobile.html, project-webperf.html to make the pages load faster by reducing overhead on the browser.

2. Optimized all the images used in all the pages to transfer less data over the wire and make the page load faster.

3. Optimized the views/js/main.js and made the following changes.

      * added all the animation changes into a map object and used the values while the scroll event occurs for better performance. Instead calculatong the location of the pizza image and placing the image at the location at every scroll event occurance.

      * removed the extra calculations part which hets executed when the scroll bar is operated.

