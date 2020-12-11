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


[return to home page](./README.md)
