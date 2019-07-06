# Virtual Keyboard
## Features
+ Automatically detects input and textarea elements within the user's project and configures them to function with the virtual keyboard
+ Automatically injects the keyboard's markup with one line of HTML
+ Full QWERTY keyboard with support for shift, caps lock, enter (return), and backspace
## How To Implement:
In the ```html <head>``` of your document, add the following element:<br>
    ```html
    <link rel="stylesheet" type"text/css" href="css/keyboard.css">
    ```
<br>At the bottom of your ```html <body>``` element, add the following lines:<br>
    ```html
    <br><script type="text/javascript" src="scripts/keyboard-initializer">
    <br><script type="text/javascript" src="scripts/keyboard-handler"><br>
    ```
<br>Wherever you would like to insert a keyboard, include the following line in your markup:<br>
    ```html
    <div class="virtual-keyboard"></div>
    ```
---
Made by Quintin Herb.
If you have any questions, feel free to email me at quintin@quintinherb.net.
