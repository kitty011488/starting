<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Document</title>

  <style>
    body {
      background-color: blue;
      color: black;
      font-family: "Comic Sans MS";
    }

    button {
      height: 50px;
      width: 50px;
      margin: 5px;
    }

    input {
      margin: 5px;
    }
  </style>

  <script>
    let total = 0;

    function AddBy() {
      let a = Number(document.getElementById("one").value);
      let b = Number(document.getElementById("two").value);
      let result = a + b;
      total += result;
      document.getElementById("result").innerHTML = "Total: " + total;
    }

    function SubBy() {
      let a = Number(document.getElementById("one").value);
      let b = Number(document.getElementById("two").value);
      let result = a - b;
      total += result;
      document.getElementById("result").innerHTML = "Total: " + total;
    }

    function MulBy() {
      let a = Number(document.getElementById("one").value);
      let b = Number(document.getElementById("two").value);
      let result = a * b;
      total += result;
      document.getElementById("result").innerHTML = "Total: " + total;
    }

    function DivBy() {
      let a = Number(document.getElementById("one").value);
      let b = Number(document.getElementById("two").value);
      if (b === 0) {
        alert("Cannot divide by zero!");
        return;
      }
      let result = a / b;
      total += result;
      document.getElementById("result").innerHTML = "Total: " + total;
    }
  </script>
</head>

<body>
  <h1>Good Afternoon</h1>

  <input type="text" placeholder="Enter 1st number:" id="one" maxlength="6" />
  <input type="text" placeholder="Enter 2nd number:" id="two" maxlength="6" />

  <br />

  <button onclick="AddBy()">Add</button>
  <button onclick="SubBy()">Sub</button>
  <button onclick="MulBy()">Mul</button>
  <button onclick="DivBy()">Div</button>

  <p id="result">Total: 0</p>

  <?php
    $name = "love";
    echo "<p>How are you? My name is $name.</p>";
  ?>
</body>
</html>
