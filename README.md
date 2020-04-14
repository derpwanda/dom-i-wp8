
# DOM I

Topics:
 * Interacting with the DOM
 * Selectors
  * selectElementsByClassname
  * selectElementbyId
  * querySelector
  * querySelectorAll
 * NodeList
 * HTMLCollection

## Objectives
 * Manipulate the DOM using JavaScript
 * Choose selectors for a given problem
 * Work with the object the different selectors return

## Beginning Project
 * You'll be working in the `digital_timer` directory
 * Add your script tag into you index.html
 * You can open your `index.html` file in your browser to see your work, but you may also work in codepen.io first if you'd like
 * All your work will be done in `index.js`
 * Make sure to read both the `index.html` and `styles.css` files so that you know what you're working with
 * Organization of your code in `index.js` will be up to you. There will be suggestions provided later in the day

## Project Description
 You will be making a timer that:
  * Counts up to 10 seconds
  * Increments every 10 ms
  * Has digits change to red when it gets to 10 seconds
  * Should not count past 10 seconds

 You will also need to look up and use `window.setInterval`. For this method, and any of those listed in the "Topics" section of this README, you are encouraged to use MDN as your resource for Documentation. MDN can be challenging to consume at first, so you may also use something like W3schools if the MDN documentation on a given subject is a bit too complicated.

# DOM I - JavaScript Content Management System

## Project Description
You are going to be emulating a content managment system by controlling the content in the JavaScript file instead of the HTML file. This project is an excercise pointed at selecting elements and then updating them without touching the HTML file using the DOM.

You have been provided a [JSON object](js/index.js) with all the necessary data to accomplish this task.  Use dot or bracket notation to traverse the data provided.

**ONE RULE: You cannot update the HTML or CSS files directly.  You must use JavaScript and the DOM only for your tasks today.**

## Task 1: Set Up The Project With Git

* [x] Fork the project into your GitHub user account
* [x] Clone the forked project into a directory on your machine
* [x] You are now ready to build this project with your preferred IDE

## Task 2: Create selectors to point your data into elements
* [ ] Create selectors by using any of the DOM element's methods
* [ ] Note that IDs have been used on all images.  Use the IDs to update src path content

## Task 3: Update the HTML with the JSON data
* [ ] Remember, NO direct updating of the HTML source is allowed.
* [ ] Using your selectors, update the content to match the example file.
* [ ] Remember to update the src attributes on images

## Task 4: Add new content
* [ ] Change the color of the navigation text to be green.
* [ ] Utilize `.appendChild()` and `.prepend()` to add two new items to the navigation system. You can call them whatever you want.
* [ ] Check your work by looking at the [original html](original.html) in the browser

## Stretch Goals
* [ ] Update styles throughout the page as you see fit.  Study what happens when you updated the DOM using style in JavaScript.  
* [ ] Study tomorrow's lesson on events and try to integrate a button that can update content on the site with a click of a button.  You could build a similar data object with new values to help you test the click event.

## Stretch Project: Digital Timer
This project is heavier on logic but employs some DOM manipulation to achieve it's goals.  Go check it out here: [stretch assignment](stretch-assignment) and see how far you can get.
