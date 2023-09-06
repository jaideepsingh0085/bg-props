# bg-props
![Screenshot 2023-09-06 231627](https://github.com/jaideepsingh0085/bg-props/assets/128147644/4b8fd80a-9c86-4fe1-a3be-7b6446dcaecc)
![Screenshot 2023-09-06 231636](https://github.com/jaideepsingh0085/bg-props/assets/128147644/df203303-ce3b-4bbc-b69f-e7cd7ff07020)
![Screenshot 2023-09-06 231649](https://github.com/jaideepsingh0085/bg-props/assets/128147644/e5a84e05-901e-42fc-aaa1-ddb68369d1c5)

HTML Description:
<!DOCTYPE html>: Declares the document type as HTML5.

<html lang="en">: The root element for an HTML document, specifying the document's language as English.

<head>: Contains metadata about the HTML document.

<meta charset="UTF-8">: Sets the character encoding of the document to UTF-8.

<meta name="viewport" content="width=device-width, initial-scale=1.0">: Defines the viewport settings for responsive web design.

<title>Document</title>: Sets the title of the web page to "Document."

<link href="./style.css" rel="stylesheet">: Links an external CSS stylesheet named "style.css" to style the page.

<body>: Contains the content of the web page.

<div class="image">: Defines a container div with the class "image."

<div class="header">: Contains a header section.

<button class="button">Home</button>: Creates a button with the text "Home."

<h2 class="nav con">Services</h2>, <h2 class="nav con">About</h2>, <h2 class="nav con">Project</h2>, <h2 class="nav con">Contract</h2>: Four heading elements (h2) with the class "nav con" for navigation links.

<div class="images">: Defines a container div for a set of images.

<img class="three" src="URL">: Three image elements with the class "three" and different image source URLs.

<div class="box">: Creates a container div with the class "box."

<img class="boximage" src="URL">: An image with the class "boximage" and a source URL.

<p class="para">: A paragraph element with the class "para" for text content.


CSS Properties :

*: Targets all elements.
margin: Sets the margin to 0 pixels.
padding: Sets the padding to 0 pixels.
box-sizing: Uses border-box as the box-sizing model.

.image: Targets elements with the class "image."
background-image: Sets a background image for the element.
height: Sets the height to 100 viewport height units (100vh).
width: Sets the width to 100 viewport width units (100vw).
background-repeat: Prevents background image repetition.
background-size: Sets the background size to cover the element.

.header: Targets elements with the class "header."
background-image: Applies a linear gradient background.
height: Sets the height to 12% of its parent container.

.nav: Targets elements with the class "nav."
display: Sets the display property to inline-block.
font-size: Sets the font size to 16 pixels.
margin-top: Adjusts the top margin by -1%.

.con: Targets elements with the class "con."
color: Sets the text color to white.
padding: Adds 4% padding to the element.

.button: Targets elements with the class "button."
background-color: Sets the background color to white.
margin-left: Adds a left margin of 10 pixels.
font-size: Sets the font size to 16 pixels.
padding: Adds 4 pixels of padding.
margin-right: Adds a right margin of 5%.

.images: Targets elements with the class "images."
background-color: Sets the background color to white.
margin-top: Adjusts the top margin to 70 viewport height units (70vh).
height: Sets the height to 500 pixels.
width: Sets the width to 100%.

.three: Targets elements with the class "three."
display: Sets the display property to inline-block.
padding: Adds 2% padding.
height: Sets the height to 500 pixels.
width: Sets the width to 33 viewport width units (33vw).

.box: Targets elements with the class "box."
background-color: Sets the background color to black.
height: Sets the height to 600 pixels.
width: Sets the width to 100%.

.boximage: Targets elements with the class "boximage."
display: Sets the display property to inline-block.
height: Sets the height to 400 pixels.
width: Sets the width to 45 viewport width units (45vw).
margin-left: Adds a left margin of 46%.
margin-top: Adds a top margin of 40 pixels.

.para: Targets elements with the class "para."
display: Sets the display property to inline-block.
width: Sets the width to 42%.
margin-top: Adjusts the top margin by -30%.
margin-left: Adds a left margin of 2%.
color: Sets the text color to white.
font-size: Sets the font size to 16 pixels.
