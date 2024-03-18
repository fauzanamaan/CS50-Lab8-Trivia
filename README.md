# CS50-Lab8-Trivia
Trivia Web Application
======================

![Trivia Questions](screenshot.png)

This repository contains my solutions for the CS50 Lab 8 project - a webpage that lets users answer trivia questions.

Getting Started
---------------

If you haven't already, follow these steps to set up the project in your environment:

1.  Open VS Code.
2.  Start by clicking inside your terminal window, then execute `cd` by itself.
3.  Execute the following command to download the project files:

    wget https://cdn.cs50.net/2022/fall/labs/8/trivia.zip
    

4.  Unzip the downloaded file:

    unzip trivia.zip
    

5.  Remove the ZIP file:

    rm trivia.zip
    

6.  Move into the project directory:

    cd trivia
    

Now you should see `index.html` and `styles.css` in your project directory.

Implementation Details
----------------------

### Part 1

*   Added a multiple-choice trivia question in `index.html`.
*   Used an `h3` heading for the question text.
*   Included buttons for each possible answer choice.
*   Implemented JavaScript logic to change button colors on click.
    *   If the user clicks on an incorrect answer, the button turns red and displays "Incorrect" beneath the question.
    *   If the user clicks on the correct answer, the button turns green and displays "Correct!" beneath the question.

### Part 2

*   Added a text-based free response question in `index.html`.
*   Used an `h3` heading for the question text.
*   Implemented an input field for the user's response.
*   Added a button to confirm the answer.
*   Implemented JavaScript logic to change input field color on confirmation.
    *   If the user types an incorrect answer and confirms, the field turns red and displays "Incorrect" beneath the question.
    *   If the user types the correct answer and confirms, the field turns green and displays "Correct!" beneath the question.

### Additional Options

*   Edited `styles.css` to customize the webpage's appearance.

Walkthrough
-----------

For a detailed walkthrough, you can refer to [this video](https://cs50.harvard.edu/x/2021/labs/8/).

Hints
-----

*   Use `document.querySelector` to query for a single HTML element.
*   Use `document.querySelectorAll` to query for multiple HTML elements that match a query.

Testing
-------

There's no `check50` for this lab as implementations will vary based on your questions. However, make sure to test both incorrect and correct responses for each question to ensure the webpage responds appropriately.

To test your webpage, run `http-server` in your terminal while in your `lab8` directory to start a web server that serves your webpage.

Feel free to customize the trivia questions or further enhance the functionality of the webpage according to your preferences!

Happy coding! 🚀
