# A-Frame Playground

The A-Frame playground gives you a tool, to load a presentation of a number of example HTML files and click through them while showing code and result in one view. Made for educational purposes to teach [A-Frame](https://aframe.io/) but can also be used with standard HTML.

You can try a [demo here](https://curious-electric.com/w/experiments/aframe/aframe-playground/playground).


## Installation
Download the zip or clone into the project.

To use it you need to install a simple HTTP Server.

On Unix-type OSes you can usually use ```python -m SimpleHTTPServer 9001```.

If you have NodeJS installed, you can install a web server with

    npm install http-server -g
    http-server -p 9001

After that, you should be able to open ```http://localhost:9001/playground``` and see this:

![screenshot](screenshot.png "Screenshot")


## Features

- fast loading of both code and render of HTML/JS on the click
- code editing via [CodeMirror/](https://codemirror.net/)
- hot reloading

There are a number of features that could be implemented additionally ( file save, autocompletion etc) but I felt the feature set was sufficient for my use case. Feel free to create issues to discuss.

## Adapt

To use your own example files, prepare them by adding a ```<!--START-->``` and ```<!--END--> ``` to the HTML which you want to showcase (see an example [here](https://github.com/dirkk0/aframe-playground/blob/master/examples/cube.html)).

Then put them into the examples directory and add them to the examples array [here](https://github.com/dirkk0/aframe-playground/blob/master/playground/index.html#L55).

