# svg_turtle
A python program that reads .svg file (and optionally 8 images for turtle's shape) using python's `turtle` module. 

![gif](https://raw.githubusercontent.com/leo3065/svg_turtle/master/gif/out.gif)

Currently only supporting files with close paths and layers with no transformation. 

## Usage

`svg_turtle.py -s SVG_PATH [-t SPRITE_PATH]`

Example: 

`svg_turtle.py -s test_input\227.svg -t "test_input\turtle_sprites\a{}_3.gif"`

