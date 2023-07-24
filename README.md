# My Favorite Cat - Mini Project #1

This mini-project is a simple HTML file that showcases JavaScript usage to modify the content of a webpage dynamically. It updates the displayed cat name and includes another cat's name using JavaScript.

## Getting Started

To view the changes made by this mini-project, open the provided HTML file named `index.html` in your web browser. No additional setup or installation is required.

## How to Use

1. Open the `index.html` file in your web browser.

2. The web page will display the heading "My Favorite Cat is" followed by the name of a cat inside a `<span>` element with the ID `catname`.

3. JavaScript code is embedded within the `<script>` tag after the `<h1>` element.

4. The JavaScript code dynamically changes the content of the cat name. The original cat name is "Zephyr," and the code appends " and Henry" to it.

5. After the JavaScript code runs, the `<span>` element's content is updated to display "Zephyr and Henry" within the `<h1>` heading.

## Code Details

The implementation uses HTML and JavaScript to modify the content of the webpage.

### JavaScript Logic

The JavaScript code inside the `<script>` tag targets the `<span>` element with the ID `catname` using `document.getElementById("catname")`. It then retrieves the current text content of the `<span>` element using `innerText`, which is "Zephyr" in this case.

The code then appends " and Henry" to the existing cat name, creating the string "Zephyr and Henry."

Finally, it updates the content of the `<span>` element by setting the `innerHTML` property to the new string "Zephyr and Henry."

## Note

- This mini-project demonstrates how JavaScript can be used to update and manipulate the content of a webpage dynamically.

- The example provided in the code is specific to cat names, but you can modify the JavaScript code to update other elements or include different text as needed.
