# htmltest
learning HTML

      <form>
        <label for="username">Enter username:</label>
        <input type="text" id = "username" placeholder="enter username" required>
      </form>


      <form>
        <label for="password">Enter password:</label>
        <input type="password" id = "password" placeholder="enter password" required>
     
        <p>Select your age:</p>

          <input type="radio" name="age"  value="0-25"  id="option-1">
          <label for="option-1"> 0-25</label>

<br>
          <input type="radio" name="age"  value="25-50"  id="option-2">
          <label for="option-2">25-50</label>

<br>

        <input type="radio" name="age"  value="50+"  id="option-3">
        <label for="option-3"> 50+</label>

<br><br>

<label for="Question">Security Question:</label>


              <select name="Question" id="Question">
        <option value="Q1">What is your best dish?</option>
        <option value="Q2">which team do you support?</option>
        <option value="Q3">your best friend's friend?</option>
              </select>

<br><br>
        <label for="QuestionAnswer">Answer:</label>
        <input type="text" id="QuestionAnswer" name="QuestionAnswer" placeholder="reply here">
      <br> <br>

        <label for="bio">Enter your bio</label> <br>
        <textarea name="bio" id="bio" cols="30" rows="20" placeholder="Enter your bio..."></textarea>

        <br> <br>
        <input type="submit" value="submit the form">


        </form>
        <!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=h, initial-scale=1.0">
    <title>About us</title>
</head>
<body>
    <h1>About us</h1>
       <p> 
        in our environment activate our desire to eat energy-rich food. So even though
           we’re not hungry, we get into the habit of picking up that extra soda or bagel.
           We can’t always avoid these triggers in our wider environment. Instead, take a 
          look at your immediate environment, such as your home or office. Research shows 
          that even small changes can make a big difference and make weight management easier
          for you.
      </p>
      !DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html>
</body>
</html>

//<html>
<head>
<title>Register</title>
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="//code.jquery.com/ui/1.11.4/jquery-ui.js"></script>
<link rel="stylesheet" href="//code.jquery.com/ui/1.11.4/themes/smoothness/jquery-ui.css">
<!--This line includes the .css file-->
<link href="http://localhost/register/formjscript.css" rel="stylesheet">
</head>
<body>
<div id="main">
<h2>Registration Form using JavaScript</h2>
<div id="form_sample">
</div> <!--This line includes the .js file-->
<script src="http://localhost/register/formjscript.js"></script>
</div>
</body>
</html>
<!DOCTYPE HTML>
<html>
<head>
<script>
function allowDrop(ev) {
  ev.preventDefault();
}

function drag(ev) {
  ev.dataTransfer.setData("text", ev.target.id);
}

function drop(ev) {
  ev.preventDefault();
  var data = ev.dataTransfer.getData("text");
  ev.target.appendChild(document.getElementById(data));
}
</script>
</head>
<body>

<div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"></div>

<img id="drag1" src="img_logo.gif" draggable="true" ondragstart="drag(event)" width="336" height="69">

</body>
</html>

<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>

<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>

//the class attributes

.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
  <h2>London</h2>
  <p>London is the capital of England.</p>
</div>

<div class="city">
  <h2>Paris</h2>
  <p>Paris is the capital of France.</p>
</div>

<div class="city">
  <h2>Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>
</div>
      
      //computer code
      <code>
x = 5;
y = 6;
z = x + y;
</code>
//The EventSource (Server Sent Event SSE)

var source = new EventSource("demo_sse.php");
source.onmessage = function(event) {
  document.getElementById("result").innerHTML += event.data + "<br>";
};

//Dragg and Drop with JS

<script>
function allowDrop(ev) {
  ev.preventDefault();
}

function drag(ev) {
  ev.dataTransfer.setData("text", ev.target.id);
}

function drop(ev) {
  ev.preventDefault();
  var data = ev.dataTransfer.getData("text");
  ev.target.appendChild(document.getElementById(data));
}
</script>
</body>
</html>
using let and var then those anot declared at all

var x = 5;
var y = 6;
var z = x + y;

let x = 5;
let y = 6;
let z = x + y;

const price1 = 5;
const price2 = 6;
let total = price1 + price2; difference between let and const

let length = 16;            // 

let lastName = "Johnson";   // 

const x = {
  firstName: "John",
  lastName: "Doe"
};    //string and bigInt, int 

