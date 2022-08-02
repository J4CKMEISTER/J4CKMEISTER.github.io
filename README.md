<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
 video {
  pointer-events: none;
}
body, html {
  height: 100%;
  margin: 0;
  font-family: Rockwell, Helvetica, sans-serif;
}

* {
  box-sizing: border-box;
}

.bg-image {
  /* Full height */
  height: 50%; 
  
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* Images used */
.img1 { background-image: url("https://user-images.githubusercontent.com/78603128/182279791-dfdb5519-55e2-4562-8fbf-e8e2a3f8a0a8.png"); }
.img2 { background-image: url("https://user-images.githubusercontent.com/78603128/182279882-6c978b51-9338-4623-8dc8-60e039d1626e.png"); }
.img3 { background-image: url("https://user-images.githubusercontent.com/78603128/182279994-e547353c-c382-45e5-bc14-e182e5d9d7ad.png"); }
.img4 { background-image: url("https://user-images.githubusercontent.com/78603128/182280145-d1728cc6-9e66-436c-9e1a-005b6fd7df2d.png"); }
.img5 { background-image: url("https://user-images.githubusercontent.com/78603128/182280221-b92e0968-953b-4dfe-9690-df930112ecdd.png"); }
.img6 { background-image: url("https://user-images.githubusercontent.com/78603128/182280267-3910fced-e645-488e-816f-8d0b93bd3476.png"); }

/* Position text in the middle of the page/image */
.bg-text {
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
  color: white;
  font-weight: bold;
  font-size: 80px;
  border: 10px solid #f1f1f1;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 600px;
  padding: 20px;
  text-align: center;
}
</style>
</head>
<body>

<div class="bg-image img1"></div>
<div class="bg-image img2"></div>
<div class="bg-image img3"></div>
<div class="bg-image img4"></div>
<div class="bg-image img5"></div>
<div class="bg-image img6"></div>

<div class="bg-text">Jackmeister</div>

</body>
</html>


