---
layout: archive
title: "Outreach"
permalink: /outreach/
author_profile: true
redirect_from:
  - /outreach
---
---

I am very passionate about exploring different creative forms of scientific outreach. Science should be for everyone, which is why I believe in creating accessible opportunites for the general public to learn about the nature of our universe. Along with speaking to middle and high school science classes, I have created outreach materials for radio and outdoor education settings. I have highlighted some of my favorites below:

## Astronomy Ranger: Exploring the dark skies of Bryce Canyon National Park
---
Bryce Canyon National Park in southern Utah was recently classified as a dark sky park by the International Dark-Sky Association, which is a testament to the clarity of its night skies as well as its commitment to darky sky education and conservation. 
Nearly 80% of North Americans can't see the Milky Way, but at Bryce Canyon it is almost a nightly occurance. 

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides1 {display: none}
img {vertical-align: middle; display: block;
  margin-left: auto;
  margin-right: auto}

/* Slideshow container */
.slideshow-container1 {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev1, .next1 {
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
  background-color: rgba(0,0,0,0.2);
}

/* Position the "next button" to the right */
.next1 {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev1:hover, .next1:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text1 {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext1 {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot1 {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active1, .dot1:hover {
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
  .prev1, .next1,.text1 {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container1">

<div class="mySlides1 fade">
  <div class="numbertext1">1 / 6</div>
  <img src='/images/bryceday.jpeg' style="height:768px">
  <div class="text1">Looking over the canyon edge at the hoodoos of Bryce Canyon National Park.</div>
</div>

<div class="mySlides1 fade">
  <div class="numbertext1">2 / 6</div>
  <img src='/images/brycenight.jpeg' style="height:768px">
  <div class="text1">Twilight at Bryce Canyon's Sunset Point, while we were setting up telescopes.</div>
</div>

<div class="mySlides1 fade">
  <div class="numbertext1">3 / 6</div>
  <img src='/images/brycetalk.jpg' style="height:768px">
  <div class="text1">Presenting my program "A Message to the Universe" at the Bryce Canyon Lodge</div>
</div>

<div class="mySlides1 fade">
  <div class="numbertext1">4 / 6</div>
  <img src='/images/brycemoon.jpeg' style="height:768px">
  <div class="text1">The moon seen through one of the telescopes at Bryce Canyon</div>
</div>

<div class="mySlides1 fade">
  <div class="numbertext1">5 / 6</div>
  <img src='/images/brycejupiter.jpeg' style="height:768px">
  <div class="text1">Jupiter shines next to a hoodoo during a full moon hike at Bryce Canyon.</div>
</div>

<div class="mySlides1 fade">
  <div class="numbertext1">6 / 6</div>
  <img src='/images/brycemilkyway.jpeg' style="height:768px">
  <div class="text1">The milky way as seen through night vision goggles.</div>
</div>

<a class="prev1" onclick="plusSlides(-1)">&#10094;</a>
<a class="next1" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot1" onclick="currentSlide(1)"></span> 
  <span class="dot1" onclick="currentSlide(2)"></span> 
  <span class="dot1" onclick="currentSlide(3)"></span>
  <span class="dot1" onclick="currentSlide(4)"></span> 
  <span class="dot1" onclick="currentSlide(5)"></span> 
  <span class="dot1" onclick="currentSlide(6)"></span>
</div>

<script>
var slideIndex1 = 1;
showSlides(slideIndex1);

function plusSlides1(n) {
  showSlides(slideIndex1 += n);
}

function currentSlide1(n) {
  showSlides(slideIndex1 = n);
}

function showSlides1(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides1");
  var dots = document.getElementsByClassName("dot1");
  if (n > slides.length) {slideIndex1 = 1}    
  if (n < 1) {slideIndex1 = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active1", "");
  }
  slides[slideIndex1-1].style.display = "block";  
  dots[slideIndex1-1].className += " active1";
}
</script>

</body>
</html> 

As an astronomy ranger intern in the summer of 2019, I spent 5 nights a week at the rim of the canyon showing visitors the night sky through telescopes. Visitors of all ages came (usually about 150 each night!), and we had great discussions about the planets, stars, black holes, our galaxy, and the stories we tell about constellations. I also led monthly full moon astronomy hikes into the canyon at night, lit only by moonlight. During the day, we would use solar telescopes to allows visitors the chance to safely look at the sun and teach them about sunspots and solar activity. I also got the opportunity to develop an evening program, which I would present biweekly to 80-100 visitors as a part of the park's normal programming as well as during the Bryce Canyon Astronomy Festival, which draws thousands of visitors each year to the park's dark skies. This program was titled "A Message to the Universe" and used the journey of the Voyager missions and the golden record to take audiences on a grand tour to the outer edge of our solar system.

## Radio Astronomy: Astronomy outreach + college radio
---
> Macalester's very own grassroots community astro talk show on WMCN. Hop on the shuttle as we blast off every week, exploring a supermassive topic in modern (astro)physics. We’ll cover it all- from the formation of the universe to the search for life, and everything in between. Anyone who wants to make contact with the cosmos should tune their receiver to ν = 91.7 MHz (λ = 3.27 m) in Saint Paul, MN or navigate to https://www.wmcn.fm/ for an hour of discovery. No previous knowledge necessary!

I have always loved public radio for its freedom to produce a variety of content without being reliant on advertisers. At Macalester College, I found college radio to be an especially good platform to experiment with different ways of communicating science to general audiences. Radio Astronomy was started by three intrepid astronomy students: Catie Ball, Alex Gordon, and Liz Ruvalo. These three were inspired by the content of their astrophysics class and wanted to share it with the rest of Macalester students as well as the surrounding community. I joined Catie and Alex as the third cohost in season 2 of the show, and as my cohosts graduated and moved on to doing other incredible science, I took on new cohosts (Sarah Taft, then Josh Bartz and Nick Velikonja) and Radio Astronomy continued on the air through a 5th season. Due to the coronavirus pandemic limiting access to the studio, Radio Astronomy is on a hiatus, but I hope that it will return someday.

### Listen to our archived episodes from seasons 2-5 [here!](https://www.mixcloud.com/radioastronomy917/)


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides2 {display: none}
img {vertical-align: middle; display: block;
  margin-left: auto;
  margin-right: auto}

/* Slideshow container */
.slideshow-container2 {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev2, .next2 {
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
  background-color: rgba(0,0,0,0.2);
}

/* Position the "next button" to the right */
.next2 {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev2:hover, .next2:hover {
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
.dot2 {
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
  .prev2, .next2,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container2">

<div class="mySlides2 fade">
  <div class="numbertext">1 / 2</div>
  <img src='/images/radioastrotelescope.jpeg' style="height:100%">
  <div class="text">Left to right: hosts Catie Ball, Riley McGlasson, and Alex Gordon with the Macalester telescope.</div>
</div>

<div class="mySlides2 fade">
  <div class="numbertext">2 / 2</div>
  <img src='/images/radioastrofinale.JPG' style="height:100%">
  <div class="text">Left to right: hosts Alex Gordon, Sarah Taft, Riley McGlasson, and Catie Ball during the season 3 finale.</div>
</div>


<a class="prev2" onclick="plusSlides(-1)">&#10094;</a>
<a class="next2" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot2" onclick="currentSlide(1)"></span> 
  <span class="dot2" onclick="currentSlide(2)"></span>
</div>

<script>
var slideIndex2 = 1;
showSlides(slideIndex2);

function plusSlides(n) {
  showSlides(slideIndex2 += n);
}

function currentSlide(n) {
  showSlides(slideIndex2 = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides2");
  var dots = document.getElementsByClassName("dot2");
  if (n > slides.length) {slideIndex2 = 1}    
  if (n < 1) {slideIndex2 = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex2-1].style.display = "block";  
  dots[slideIndex2-1].className += " active";
}
</script>

</body>
</html> 
