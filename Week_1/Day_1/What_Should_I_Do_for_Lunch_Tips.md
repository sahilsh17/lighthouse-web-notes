### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript

onst whatToDoForLunch = function(hungry, availableTime) {

  if (hungry && availableTime < 20) {
    console.log("Pick something up and eat in the kitchen");
  } else if (hungry && availableTime >= 20 && availableTime < 30) {
    console.log("Try to go to a place nearby and eat there");
  } else if (hungry && availableTime > 30) {
    console.log("You are in the bootcamp and should reconsider");
  } else if (!hungry) {
    console.log("Get back to work!");
  }
};
```