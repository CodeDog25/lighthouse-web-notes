### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("I don't know what to do!");
  } else if (hungry === true, availableTime < 20) {
    console.log("Grab a snack at home!");
  } else if (hungry === true, availableTime >= 20 && availableTime <= 30) {
    console.log("Cook a tasty meal!");
  } else if (hungry === true, availableTime > 30) {
    console.log("this is an intense program!");
  }
  return whatToDoForLunch;
};