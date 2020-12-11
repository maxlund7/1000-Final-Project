# Code Sample

Below you will find a sample of some code I wrote this year during class. This code is from a challenge we did in class called the FizzBuzz challenge.

### HTML
```html
<!DOCTYPE html>
<html>
   <head>
       <meta charset="UTF-8">
       <title>Fizz Buzz</title>

       <script>
           function fizzbuzz() {
           var display = document.getElementById('display');
           var displayHTML = "";
           for (i = 0; i < 100; i++) {
           displayHTML += "<p>" + i + "</p>";
           }
           display.innerHTML = displayHTML;
           }
       </script>
   </head>
   <body onload="fizzbuzz()">
       <div id="display">
       </div>
   </body>
</html>
```
 ## This is a sample of code from python
 
import turtle

max= turtle.Turtle()

max.color("blue")
max.speed(30)

for i in range(40):
    max.forward(300)
    max.left(170)
max.penup()
max.left(135)
max.forward(100)
max.left(45)
max.forward(100)
max.pendown()

#makes star

max.color("red")
max.right(45)
max.forward(100)
max.right(135)
max.forward(100)
max.left(100)
max.forward(100)
max.right(135)
max.forward(100)

#makes M

turtle.done()


[return to home page](./README.md)
