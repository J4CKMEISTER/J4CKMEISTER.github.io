
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
  position: fixed;
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

<body>
  <center>
<video width="70%" autoplay muted loop id="myVideo">
  <source src="https://user-images.githubusercontent.com/78603128/170877724-332269f6-0f7d-4ea0-a723-8ba7e1c3a7ac.mp4" type="video/mp4">
 
</video>
  </center>
<center>
<div class="content">
  <p><h1>Hello world ! This is my personal website created to soley share the experience of information security that I learnt along
  the journey in the cyber security industry</h1></p>
  <button id="myBtn" onclick="myFunction()">Pause</button>
</div>
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
</script>

</body>
</html>
