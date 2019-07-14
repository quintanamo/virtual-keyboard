# Virtual Keyboard

## Features

+ Automatically detects input and textarea elements within the user's project and configures them to function with the virtual keyboard (inputs' types must be set to either text or password)
+ Automatically injects the keyboard's markup with one line of HTML
+ Full QWERTY keyboard with support for shift, caps lock, enter (return), and backspace

## How To Implement:

First, add the scripts and css folders contained within this repository to your project.

<br>In the `<head>` of your document, add the following element:<br>
  `<link rel="stylesheet" type="text/css" href="css/keyboard.css">`
  
<br>At the bottom of your ```<body>``` element, add the following lines:<br>
  `<script type="text/javascript" src="scripts/keyboard-initializer.js"></script>`
  <br>`<script type="text/javascript" src="scripts/keyboard-handler.js"></script>`
  <br>*Please note that you may have to change the file paths within the script tags' src attributes.*
  
<br>Wherever you would like to insert a keyboard, include the following line in your markup:<br>
  `<div class="virtual-keyboard"></div>`
  
---

Made by Quintin Herb.
If you have any questions, feel free to email me at quintin@quintinherb.net.
