"# CSC102 - Game

I utilized the plugin "Flip Counter" by PQINA (https://pqina.nl/flip/?ref=pqina) in order to keep track of the numbers in a clean way. I didn't integrate their style sheets or anything to mine so it can easily be identified by you. Their files are:

- config/css/flip.min.css
- config/js/flip.min.js

I had my own counter that I was making progress with, but ran into an issue where it relied on span's inside of a div with some CSS to work, it moved by modifying something with ".counter span{" inside the CSS, but I couldn't accomplish the same in the Javascript and therefore couldn't be tied in to keep track of numbers manually. I'm sure there's a way to do it, but after asking a programming Discord I'm in the solution was extremely tedious and involved addressing each span individually and using a lot of math.
___________

The colors can be changed by clicking the dice on the left side, and all stats are tracked up to 99 at which point they integer overflow to 00.
