# GC_VeganBurger

<!DOCTYPE html>
<html>
<head>
<link href="https://fonts.googleapis.com/css?family=Oswald|PT+Sans" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Catamaran|Fjalla+One" rel="stylesheet">
<title>Vegan Burger</title>
<!-- item 26-->
        <link rel="icon"
          type="image/png"
          href="Basil_Leaves.png"
          />
<link rel="stylesheet" type="text/css" href="Gc_VeganBurger.css">
</head>
<!-- item 26-->
        <link rel="icon"
          type="image/png"
          href=""
          />
<!--slide area-->

  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="VeganBurger1.jpeg" style="width:100%">
    <div class="text">Superiority Burger</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="VeganBurger2.jpg" style="width:100%">
    <div class="text">Superiority Burger</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    <img src="VeganBurger3.jpg" style="width:100%">
    <div class="text">Superiority Burger</div>
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

<h1>Superiority Burger NYC</h1>

<body>
    <p>Looking for a healthy version of fast food? Take a trip down to the East Village to find Superiority Burger-an entire vegan burger menu. The menu itself is constantly changing from one thing to another.</p>


<!-- item 13-->   
<h3>Some Items on The Current Menu</h3>
<ul>
  <li>Burnt Broccoli Salad</li>
  <li>Arnold Palmer
    <ul>
      <li>Just the right amount of Lemonade and Tea</li>
      <li>Not too sweet</li>
    </ul>
  </li>
  <li>Ranch Romaine Salad</li>
</ul>
    
    
    
<p>For more menu items<a href="http://www.superiorityburger.com/menu/">Visit Superiority Burger's Website</a></p>
    <p>&copy; Superiority Burger</p>
</body>
</html>
