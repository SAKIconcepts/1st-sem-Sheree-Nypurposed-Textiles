
  
<!DOCTYPE html>
<html>
<head>
<style>
/* Styles for navbar */
.nav {
  background-color: #c9d8c6;
  list-style-type: none;
  text-align: center;
  margin: 0;
  padding: 0;
  position: relative; /* Position relative for positioning the logo */
}


.nav img {
  position: absolute;
  left: 30px; /* Adjust left position as needed */
  top: 50%;
  transform: translateY(-50%);
  height: 40px; /* Adjust height as needed */
}


.nav li {
  display: inline-block;
  font-size: 20px;
  padding: 20px 50px;
}


/* Style for h1 and h2 */
h1, h2 {
  text-align: center; /* Center align */
  font-weight: bold; /* Bold font */
  font-family: Comic sans, sans-serif; /* Font family */
  margin-top: 40px; /* Top margin */
  margin-bottom: 20px; /* Bottom margin */
  text-transform: capitalize; /* Capitalize first letter of each word */
}


/* Style for images */
/* Style for images */
.mySlides img {
  display: block; /* Make images block-level elements */
  margin: 2px auto; /* Center align images horizontally */
  max-width: 75%; /* Ensure images don't exceed container width */
  max-height: 500px; /* Limit the maximum height of the images */
  width: auto; /* Automatically adjust width while maintaining aspect ratio */
}


/* Keep the active slide's image at its original size */
.mySlides .active img {
  max-width: none; /* Reset max-width property */
  max-height: none; /* Reset max-height property */
}





/* Style for footer */
.footer {
  background-color: #3acfc8; /* Lighter version of navbar color */
  text-align: center;
  padding: 20px;
  position: absolute;
  bottom: -100%;
  left: 0px; /* Stick to the bottom */
  width: 100%; /* Full width */
  z-index: 999; /* Ensure the footer appears above other content */
}


/* Style for social media icons */
.footer a {
  color: #eff7f8; /* Dark color for icons */
  text-decoration: none;
  font-size: 24px;
  margin: 100px, 10px;
}
</style>
</head>

<body>
 


<!-- Navbar -->
<ul class="nav">
  <img width="50" height="80" src="https://www.bloomingetiquette.dk/wp-content/uploads/2024/05/Volacano.jpg" alt="Logo"> <!-- Add your logo here -->
  <li><a href="#Home">Hjem</a></li>
  <li><a href="#Blog">Blog</a></li> 
  <li><a href="#Kalender">Kalender</a></li>
  <li><a href="#About">Om os</a></li>
  <li><a href="#Kontakt">Kontakt os</a></li>
</ul>





<h1 style="color:rgb(57, 99, 70);">Nye produkter fra genandvendelige Materialer</h1>


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
  animation-name: fade;
  animation-duration: 1.5s;
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
  <div class="numbertext">1 / 3</div>
  <img src="https://www.bloomingetiquette.dk/wp-content/uploads/2024/05/21-scaled.jpg" style="width:100%">
  <div class="text">Acoustic Panel by HAACK</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="https://www.bloomingetiquette.dk/wp-content/uploads/2024/05/pusletaske-.jpg" style="width:100%">
  <div class="text">Shopper bag in the making</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://www.bloomingetiquette.dk/wp-content/uploads/2024/05/babydressbyDorte.jpg" style="width:100%">
  <div class="text">Baby Dress by Dorte</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://www.bloomingetiquette.dk/wp-content/uploads/2024/05/IMG_6984.jpg" style="width:100%">
  <div class="text">By Ringsted Re-Design</div>
</div>



<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 8000); // Change image every 8 seconds
}


</script>
</body>
</html> 



<!DOCTYPE html>
<html>
<style>
body {font-family: Arial, Helvetica, sans-serif;}

form {
  border: 3px solid #f1f1f1;
  font-family: Arial;
}

.container {
  padding: 20px;
  background-color: #f1f1f1;
}

input[type=text], input[type=submit] {
  width: 100%;
  padding: 12px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

input[type=checkbox] {
  margin-top: 16px;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  border: none;
}

input[type=submit]:hover {
  opacity: 0.8;
}
</style>
<body>



<h2>Bliv Inspireret</h2>


<head>
  <style>
  * {
    box-sizing: border-box;
  }
  
  .img-container {
    float: left;
    width: 33.33%;
    padding: 5px;
  }
  
  .clearfix::after {
    content: "";
    clear: both;
    display: table;
  }
  </style>
  </head>
  <body>
  
  <h2>Vi har samlet de bærdygtige koncepter for dig</h2>
  
  
  <div class="clearfix">
    <div class="img-container">
    <img src="https://www.bloomingetiquette.dk/wp-content/uploads/2024/05/Vibeke.jpg" alt="Italy" style="width:100%">
    </div>
    <div class="img-container">
    <img src="https://www.bloomingetiquette.dk/wp-content/uploads/2022/01/IMG_5082-scaled.jpg" alt="Forest" style="width:100%">
    </div>
    <div class="img-container">
    <img src="https://www.bloomingetiquette.dk/wp-content/uploads/2024/05/20240521151659_IMG_6891-1.jpg" alt="Mountains" style="width:100%">
    </div>
  </div>
  

  
<form action="submit">
  <div class="container">
    <h2>Tilmeld Nyhedsbrev</h2>
    <p>Vil du være med i de kommende begivenheder i din lokale by? Så, lad os komme i gang. Vi sender nyhedsbreve ugentligt og hver anden måned. Nemt afmelding.</p>
  </div>

  <div class="container" style="background-color:rgb(113, 175, 149)">
    <input type="text" placeholder="Name" name="name" required>
    <input type="text" placeholder="Email address" name="mail" required>
    <label>
      <input type="checkbox" checked="checked" name="subscribe"> Ugentligt Nyhedsbreve
    </label>
  </div>

  <html>
    <head>
    <style>
    a:link, a:visited {
      background-color: ##c3e3cc;
      color: light green;
      padding: 14px 25px;
      text-align: center;
      text-decoration: bold;
      display: inline-block;
    }
    
    a:hover, a:active {
      background-color: rgb(42, 129, 122);
    }
    </style>
    </head>
    <body>
      
    <p>Ved at trykke på tilmeld, du har læst vores data opbevaringpolitik</p>
    <a href="https://bloomingetiquette.dk" target="_blank">Tilmeld</a>
    
    </body>
    </html>


    <!DOCTYPE html>





