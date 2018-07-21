# AFrame Playground

The AFrame playground gives you a tool, to load a presentation of a number of example HTML files and click through them while showing code and result in one view. Made for educational purposes to teach [A-Frame](https://aframe.io/) but can also be used with standard HTML.

## Installation
Download the zip or clone into the project.

To use it you need to install a simple HTTP Server.

On Unix-type OSes you can usually use ```python -m SimpleHTTPServer 9001```.

If you have NodeJS installed, chances are that this works:
```http-server -p 9001```.

If not, you can install it with 

    npm install http-server -g

After that, you should be able to open ```http://localhost:9001/playground``` and see this:

![screenshot](screenshot.png "Screenshot")

