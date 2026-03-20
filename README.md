# Assignment 1B - Hobby Web Page
*DUE: Monday, March 24 by 11:59pm.  
Late penalty of 5 points (out of 50 total points) if submitted by Tuesday, March 25 by noon.*

**Enter your first name followed by your last name below. If we cannot figure out who did the assignment, we cannot grade it!**
### Name: 
---
Use this assignment to get up to speed with git, GitHub, HTML, and CSS and using the Webstorm IDE. When you have completed the assignment, make sure to push your repository to your assignment 1b github repository.

## Assignment Details
* Use Webstorm to clone this repository on your computer.
  * Close any currently open projects.
  * Click on `Get from VCS` and enter the URL of your GitHub assignment1b repo
  * Create a `public` folder for your images and styles. 
* In the top directory of the project, create `index.html` that is a web page about your favorite hobby. Refer to the HTML tutorial at [W3 Schools](https://www.w3schools.com/html/) or elsewhere, if needed. You will include the following HTML elements below **in order**: 
  * Using the `<nav>` tag and unordered lists as mentioned in class, create horizontal navigation menu at the top of `index.html`. The menu will include links to three websites related to your hobby. You will want to research the a: pseudo classes, such as a:hover, to create styles for the menu selections.
  * Title (use a `<h1>` tag) that consists of your name and your hobby
  * A rectangular image related to your hobby (sort of like a banner for the web page). You may use an AI image generator like [https://deepai.org/styles](https://deepai.org/styles) to create the image if you want. Resize the image so the width is no larger than 640 pixels. The image should be located in the `public` folder.
  * A paragraph (`<p>` tags) that introduces you
  * A paragraph that introduces your hobby
  * A list with at least 5 items
  * A table of minimum size 3 columns and 4 rows populated with relevant data in each cell, and with a table caption. Create a class with name `collapse` for the table tag.
  * A form that includes the following elements
    * at least 2 text input boxes
    * at least 3 check boxes
    * at least 3 radio buttons. Make sure that only one button can be depressed at a time!
    * at least 1 textarea for comments
    * a dropdown selection list
    * Submit button (use the `<button>` tag). This will not do anything for now.
    * Use labels for all input types to make it clear what they are for.
    * a link to the CSS stylesheet
* Create a file `mystyles.css` in the `public` folder. The file will the following CSS styles for your web page:
    * styles necessary to create a visually appealing top menubar mentioned above
    * determine visually appealing background and text colors for your entire web page
    * heading tags are a different color and font than the rest of the page
    * the first item on your list is a different color from the rest of the page
    * create a style for the HTML table class with the name `collapse`. This style specifies collapsed borders (single border rather than the default double border) with a visible border
 * Copy the file `server.js` from Canvas -> Assignments -> Assignments -> Assignment 1B to the same folder that `index.html` resides. Run the following commands to install the node.js packages for the server.
    * npm install -D express
    * npm install -D path
    * run server.js and test the URL localhost:3000 to see your web page
---




