<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>practice</title>
  <style>
    #bulb {
      width: 100px;
      height: 100px;
     border: 2px solid black;
      border-radius: 50%;
    }
    button {
  padding: 10px;
      border-radius: 5px;
      margin: 20px;
      background-color: green;
      color: white;
    }
  </style>
</head>
<body>

  <h1>This is JS</h1>
  <div id="bulb">
    
  </div>
  <button>On</button>

  <script>
var a = document.querySelector("h1")
    a.innerHTML = "hey This is sakshi";
    console.log(a);

    a.style.backgroundColor = "red";

    a.style.color = "white";
    

    a.addEventListener("click", function() {
  document.querySelector("h1")
      a.innerHTML = "why you again change me";
      a.style.backgroundColor = "green";
      a.style.color = "yellow";
    })

    var bulb = document.querySelector("#bulb");
    var btn = document.querySelector("button");

    var flag = 0;
    btn.addEventListener("click", function() {
      if (flag == 0) {
        bulb.style.backgroundColor = "yellow";
        console.log("on");
        flag = 1;
      } else {
        bulb.style.backgroundColor = "transparent";
        console.log("off");
        flag = 0;
      }
      
    })
  </script>
</body>
</html>
