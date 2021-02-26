---
layout: archive
title: "Outreach"
permalink: /outreach/
author_profile: true
redirect_from:
  - /outreach
---

I am very passionate about exploring different creative forms of scientific outreach. Science should be for everyone, which is why I believe in creating accessible opportunites for the general public to learn about the nature of our universe. Along with speaking to middle and high school science classes, I have created outreach materials for radio and outdoor education settings. I have highlighted some of my favorites below:

## Astronomy Ranger: Exploring the dark skies of Bryce Canyon National Park
Bryce Canyon National Park in southern Utah was recently classified as a dark sky park by the International Dark-Sky Association, which is a testament to the clarity of its night skies as well as its commitment to darky sky education and conservation. 
Nearly 80% of North Americans can't see the Milky Way, but at Bryce Canyon it is almost a nightly occurance. 

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 6</div>
  <img src='/images/bryceday.jpeg' style="text-align:center; height:768px">
  <div class="text">Caption Text</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 6</div>
  <img src='/images/brycenight.jpeg' style="text-align:center; height:768px">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 6</div>
  <img src='/images/brycetalk.jpg' style="text-align:center; height:768px">
  <div class="text">Caption Three</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 6</div>
  <img src='/images/brycemoon.jpeg' style="text-align:center; height:768px">
  <div class="text">Caption Three</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 6</div>
  <img src='/images/brycejupiter.jpeg' style="text-align:center; height:768px">
  <div class="text">Caption Three</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 6</div>
  <img src='/images/brycemilkyway.jpeg' style="text-align:center; height:768px">
  <div class="text">Caption Three</div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

</body>
</html> 

As an astronomy ranger intern in the summer of 2019, I spent 5 nights a week at the rim of the canyon showing visitors the night sky through telescopes. Visitors of all ages came (usually about 150 each night!), and we had great discussions about the planets, stars, black holes, our galaxy, and the stories we tell about constellations. I also led monthly full moon astronomy hikes into the canyon at night, lit only by moonlight. During the day, we would use solar telescopes to allows visitors the chance to safely look at the sun and teach them about sunspots and solar activity. I also got the opportunity to develop an evening program, which I would present biweekly to 80-100 visitors as a part of the park's normal programming as well as during the Bryce Canyon Astronomy Festival, which draws thousands of visitors each year to the park's dark skies. This program was titled "A Message to the Universe" and used the journey of the Voyager missions and the golden record to take audiences on a grand tour to the outer edge of our solar system.

