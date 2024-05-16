<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Photo Gallery</title>
<link rel="stylesheet" href="./styles.css">
<style>
  * {
    box-sizing: border-box;
  }
  .para {
    border-style: double;
    border-color: #CE52FB;
    color: #AA336A;
  }
  body {
    margin: 0;
    background-image: linear-gradient(pink, #AA336A);
    font-family: "Times New Roman", Times, serif;
  }
  .header {
    text-align: center;
    text-transform: uppercase;
    padding: 32px;
    background-color: #AA336A;
    color: #fff;
    border-bottom: 4px solid purple;
  }
  .gallery {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 16px;
    max-width: 1400px;
    margin: 0 auto;
    padding: 20px 10px;
  }
  .gallery img {
    width: 100%;
    max-width: 350px;
    height: 300px;
    object-fit: cover;
    border-radius: 10px;
  }
  .gallery::after {
    content: "";
    width: 350px;
  }
  img:hover {
    transform: scale(1.2);
  }
  .photo {
    text-align: center;
  }
  .earth {
    text-align: center;
  }
  .garden {
    text-align: center;
  }
  .pi {
    text-align: center;
  }
  h2 {
    color: #72554F;
    text-align: center;
  }
  p {
    text-align: center;
  }
  .project1 {
    float: left;
    margin: 10px;
  }
  .project2 {
    float: right;
    margin: 10px;
  }
  .project3 {
    float: right;
    margin: 10px;
  }
  .project4 {
    position: relative;
    float: left;
    margin: 20px;
    top: -50px;
  }
  .canvas {
    -webkit-animation: move 3s linear;
    -moz-animation: move 3s linear;
    -o-animation: move 3s linear;
    -ms-animation: move 3s linear;
    animation: move 3s linear;
    -webkit-transform-style: preserve-3d;
    -moz-transform-style: preserve-3d;
    -o-transform-style: preserve-3d;
    -ms-transform-style: preserve-3d;
    transform-style: preserve-3d;
  }
  @-webkit-keyframes move {
    0% {
      -webkit-transform: rotateY(0) rotatex(0);
    }
    50% {
      -webkit-transform: rotateY(90deg) rotateX(90deg);
    }
    100% {
      -webkit-transform: rotateY(-360deg) rotateX(360deg);
    }
  }
  @-moz-keyframes move {
    0% {
      transform: rotateY(0) rotatex(0);
    }
    50% {
      transform: rotateY(90deg) rotateX(90deg);
    }
    100% {
      transform: rotateY(-360deg) rotateX(360deg);
    }
  }
  @-o-keyframes move {
    0% {
      transform: rotateY(0) rotatex(0);
    }
    50% {
      transform: rotateY(90deg) rotateX(90deg);
    }
    100% {
      transform: rotateY(-360deg) rotateX(360deg);
    }
  }
  @-ms-keyframes move {
    0% {
      transform: rotateY(0) rotatex(0);
    }
    50% {
      transform: rotateY(90deg) rotateX(90deg);
    }
    100% {
      transform: rotateY(-360deg) rotateX(360deg);
    }
  }
  @keyframes move {
    0% {
      transform: rotateY(0) rotatex(0);
    }
    50% {
      transform: rotateY(90deg) rotateX(90deg);
    }
    100% {
      transform: rotateY(-360deg) rotateX(360deg);
    }
  }
  div.absolute {
    position: absolute;
    z-index: -1;
    top: 80px;
    right: 0;
    width: 200px;
    height: 1px;
  }
</style>
</head>
<body>
<div class="canvas">
<header class="header">
<h1>Our Projects</h1>
</header>
<div class="para">
<p>This year in our class reviews HTML and CSS. <br> Then we started learning JavaScript and Python. <br>We would do different practices for different types of codes. <br> We have had many practices and fun during our time in Mr.Z class. <br> There are a few examples of projects that we all did.</p>
</div>
<div class="project1">
<h2>Photo Gallery</h2>
<div class="blue1">
<p> We did our photo gallery project <br> in the start of the year to test out our HTML and CSS skills. <br> This project entails pictures of different cities <br> around the world in a box format showcasing <br> our positioning skills in CSS and setting up div tags in HTML.
</p>
</div>
<div class="photo">
<a href="https://codepen.io/LiliennCarpenter/pen/yLZRxXa"> <img src="https://images.pexels.com/photos/51383/photo-camera-subject-photographer-51383.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Photo Gallery" style="width:300px;height:300px;"></a>
</div>
</div>
<div class="project2">
<h2>Earth Day</h2>
<p> Our Earth day project was assigned to us to celebrate Earth Day. <br> This project was made to recreate a real website. <br> Our site is a replica of earthday.org<br> To make this replica we made practiced our CSS and HTML skills.</p>
<div class="earth">
<a href="https://codepen.io/LiliennCarpenter/pen/ZEZwjLK"> <img src="https://images.pexels.com/photos/87651/earth-blue-planet-globe-planet-87651.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Earth Day" style="width:300px;height:300px;"></a>
</div>
</div>
<div class="project3">
<h2>Visual design</h2>
<p> Our Visual design project was a project based on Free Code Camp. <br> We were asked to change the code and improve the projects design. <br> In this project we mainly focused on spotlighting our vast CSS designing skills. <br>In the project we changed the basic code to a site for a local vegetable market. </p>
<div class="garden">
<a href="https://codepen.io/zoeyserino23/pen/poBMONo?editors=1100"> <img src="https://images.pexels.com/photos/158028/bellingrath-gardens-alabama-landscape-scenic-158028.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Visual Design" style="width:300px;height:300px;"></a>
</div>
</div>
<div class="project4">
<h2>Raspberry Pi</h2>
<p> This Fitness project was our midterm project.<br> We were asked to make a form for people to sign up <br> for a new and upcoming fitness company. <br> This project was an assignment we had a limited time to complete.<br> The fitness project was to test our basic knowledge <br> in coding to see if we are able to complete coding assignments in a specific time.</p>
<div class="Pi">
<a href="https://codepen.io/LiliennCarpenter/pen/oNRXMdJ"> <img src="https://images.pexels.com/photos/2177473/pexels-photo-2177473.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Fitness" style="width:300px;height:300px;"></a>
</div>
</div>
</div>
</body>
</html>
