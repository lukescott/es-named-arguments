## ECMAScript Named Arguments ##

This proposal introduces named arguments.

Works well with [es-type-hinting](https://github.com/lukescott/es-type-hinting/blob/master/README.md).

### Examples ###

Long form:
```javascript
function move(xPos: x Number, yPos: y Number) {
  console.log("x:", x, "y:", y);
}
move(xPos: 5, yPos: 10);
```

Shorthand form:
```javascript
function move(x: Number, y: Number) {
  console.log("x:", x, "y:", y);
}
move(x: 5, y: 10);
```

### Syntax ###
  TODO
