# Homework 2 - Graphical User Interface 1
## UML, Professor Zhou, Computer Science
## Student: Patricia Antlitz
## Date: 05/26/2024

Github Pages:
https://patybn3.github.io/HW_2_PA/

### Assignment:

- Edit ONLY the pacific.css file. Do not change anything in the .html file --> no comment added to HTML due to this rule.

A HTML code was provided by the instructor together with an initial css code. The goal of the assignment is to style the page in accordance with the picture provided by the instructor. Refer to ./HW2_read for the sample images. The assignment reads:

[x] The 'main' area of the page is 80% of the page width, but with a 600px minimum. It is centered in the browser.

[x] The navigation bar has a fixed width, while the content to the right of the navigation varies.

[x] The gradient background is done with the image provided (ptrbackground) but does not continue down the page. 

[x] The page is solid #00569f below the gradient.

[x] Notice that the bulleted list uses as special bullet (included with your files as marker.gif), and note how that bullet aligns with the paragraph above it.

[x] The resort name gets special coloring in the main page content.

[x] There are no bullets or underlining with the navigation links.


#### Example Image Provided:

![image](https://github.com/patybn3/HW_2_PA/assets/59259041/7e5729b7-558d-488a-8f8d-186a7f26a733)

#### Original CSS:

```
header, hgroup, nav, footer, figure, figcaption, aside, section, article {
	display: block;
}
body {
	background-color: ;
	color: #666666;
	font-family: Arial, Helvetica, sans-serif;
}

nav ul {
	font-size: 1.2em;
}
nav a:visited {
	color: #344873;
}
nav a:hover {
	color: #FFFFFF;
}
h1 {
	margin-bottom: 0;
	padding: 10px;
}
h2 {
	color: #3399CC;
}
h1,
h2 {
	font-family: Georgia, "Times New Roman", serif;
}
#contact {
	font-size: 90%;
}
dt {
	color: #000033;
}
footer {
	font-family: Georgia, "Times New Roman", serif;
}

```

#### New CSS:

Refer to code source.

Validaded with W3C CSS Validation Service: https://jigsaw.w3.org/css-validator/

### RUN

to run the source code, open the html file on your browser, or run the command `python3 -m http.server` on the terminal inside of the repository's folder

### Dependencies

No dependencies necessary

### Technologies Used:

- HTML5
- CSS 5

### Issues

No issues encountered.

### Sources:
RGB color picker:
Digital Color Meter form macOS

w3Schools CSS:
https://www.w3schools.com/css/css_navbar_horizontal.asp

Class Material
