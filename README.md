##Colors.js for Meteor

Meteor wrapper for [Colors.js](https://github.com/Marak/colors.js)  

_At the moment only suppported on the server._  

####Usage
````javascript
//server
console.log('red'.red)
console.log('green'.green)
console.log('blue'.blue)

console.log('~~~~~~'.grey)

console.log('R'.red + 'G'.green + 'B'.blue)

console.log('~~~~~~'.grey)

var test = 'ALLTHECOLORS';
console.log(test.rainbow);
````
<img src="https://raw.githubusercontent.com/nooitaf/meteor-colors/master/screenshot.jpg" alt="screenshot.jpg">


## Installation

    mrt add colors

## colors and styles!

- bold
- italic
- underline
- inverse
- yellow
- cyan
- white
- magenta
- green
- red
- grey
- blue
- rainbow
- zebra
- random


# Creating Custom themes

```js
colors.setTheme({
  silly: 'rainbow',
  input: 'grey',
  verbose: 'cyan',
  prompt: 'grey',
  info: 'green',
  data: 'grey',
  help: 'cyan',
  warn: 'yellow',
  debug: 'blue',
  error: 'red'
});

// outputs red text
console.log("this is an error".error);

// outputs yellow text
console.log("this is a warning".warn);
```


### Contributors 

Marak (Marak Squires)
Alexis Sellier (cloudhead)
mmalecki (Maciej Małecki)
nicoreed (Nico Reed)
morganrallen (Morgan Allen)
JustinCampbell (Justin Campbell)
ded (Dustin Diaz)
