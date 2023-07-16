# StarGenerator
A simple script that generates a star map using JS and animates them using CSS

[Check it out](https://imforpeace.github.io/StarGenerator/)

# How it works
## JS script:
1. Reads  viewport width and its' scaling
2. Using the global and level specific population variables generates 3 different sizes of stars. Each star array contains spawn points and color coding of each star.
3. The script joins the array and pushes it as a box-shadow style into respective "stars" classes.
## CSS
• The file has two global variables:
1. --shouldblur : boolean value to enable/disable blur effect on all stars.
2. --shouldcircle : boolean value to enable/disable stars being circles instead of squares.