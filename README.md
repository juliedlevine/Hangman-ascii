# Hangman ASCII Art
---

## What It Is
This is a module

## How to Use
In your terminal:
```
npm install hangman-ascii
```

At the top of your file:
```JavaScript
var hangman = require('hangman-ascii');
```

Call the function when you want to draw a hangman. The function takes 2 arguments.

- The first is the level hangman you want to draw. This argument takes a number from 0 to 6. 0 will be the starting point, with no hangman parts drawn. 6 will be the full hangman, meaning the player has lost.

- The second argument is a color. You pass a color in as a string. The viable colors you can pass in are: 'red' 'green' 'yellow' 'blue' 'magenta' 'cyan' 'white' 'gray' 'black'

This code will draw level 4 in a cyan blue.
```JavaScript
hangman.drawLevel(4, 'cyan');
```
<p> Depending on your terminal theme settings you will get something that looks like this:
    <img src='https://github.com/juliemdyer/Hangman-ascii/blob/master/screenshots/level_4_cyan.png'</img>
</p>
