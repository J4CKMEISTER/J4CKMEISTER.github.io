
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Rockwell;
  font-size: 17px;
}

#myVideo {
  width: 70%;
  right: 0;
  bottom: 0;
}

.content {
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
}

#myBtn {
  width: 200px;
  font-size: 18px;
  padding: 10px;
  border: none;
  background: #000;
  color: #fff;
  cursor: pointer;
}

#myBtn:hover {
  background: #ddd;
  color: black;
}
</style>
</head>

<body onload="typeWriter()">
  <center>
<video autoplay muted loop id="myVideo">
  <source src="https://user-images.githubusercontent.com/78603128/182293714-5fc8a23d-fc97-445b-a28a-4de4744e9d6e.mp4" type="video/mp4">
 
</video>
  </center>




<center>
<div class="content">
  <h1><p id ="helloworld"></p>Hello world ! This is my personal website created soley for the purpose of sharing my experience of information security that I learnt along
  the journey in the cyber security industry</h1>
  <button id="myBtn" onclick="myFunction()">Pause</button>
</div>
  <br/>
  <div id="CounterVisitor"></div>
</center>
<script>
var video = document.getElementById("myVideo");
var btn = document.getElementById("myBtn");

function myFunction() {
  if (video.paused) {
    video.play();
    btn.innerHTML = "Pause";
  } else {
    video.pause();
    btn.innerHTML = "Play";
  }
}
  

   var n = localStorage.getItem('on_load_counter');

    if (n === null) {
        n = 0;
    }

    n++;

    localStorage.setItem("on_load_counter", n);

    document.getElementById('CounterVisitor').innerHTML = 'you have visited this page '+ n + ' times';

                     
</script>

</body>
</html>
