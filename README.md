# Virtual Keyboard
## Features
+ Automatically detects input and textarea elements within the user's project and configures them to function with the virtual keyboard
+ Automatically injects the keyboard's markup with one line of HTML
+ Full QWERTY keyboard with support for shift, caps lock, enter (return), and backspace
## How To Implement:
In the ```html<head>``` of your document, add the following element:
    ```html
    <br><link rel="stylesheet" type"text/css" href="css/keyboard.css"><br>
    ```
At the bottom of your ```html<body>``` element, add the following lines:
    ```html
    <br><script type="text/javascript" src="scripts/keyboard-initializer">
    <br><script type="text/javascript" src="scripts/keyboard-handler"><br>
    ```
Wherever you would like to insert a keyboard, include the following line in your markup:
    ```html
    <br><div class="virtual-keyboard"></div><br>
    ```
---
Made by Quintin Herb.
If you have any questions, feel free to email me at quintin@quintinherb.net.
