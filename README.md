

<html>
<head>
<title> Sabbir's Personal Website</title>
<meta name="Sabbir Hossain" content="width=device-width, initial-scale=1">
<style>
font-style: serif;
color: #777777;
line-height:25px ;
}
.blue{
color: #1E90FF ;
}
.box{
width: 50%;
float: left;
}
h3 {

}
.img { 
width: 80%;
padding-left:10% ;
margin-top: 20px;
margin-bottom: 20px;
}

.container{
padding-left: 5%;
display: inline-block;
}
.btn{
color: white;
background-color: #4169E1;
padding:15px 12px 14.5px 11.2px ;
border-radius: 5px;
text-decoration: none;
margin-bottom: 20px;
}
.itm{
border: 1.5px solid #00CED1;
margin:1px ;
padding:10px ;
border-radius: 20px;
background-color: lightyellow;
width:300px;
}
.bom{
color: #1E90FF;
}
font-style: serif;
color: #777777;
line-height:25px ;
}
.blue{
color: #1E90FF ;
}
.box{
width: 50%;
float: right;
}
h3 {

}
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: HD}
img {vertical-align: middle right;}



/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: side corner;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: Green;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}



/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 20px;
  padding: 10px 9px;
  position: middle;
  bottom: 8px;
  width: 20%;
  text-align: center;
  background-color:Blue;
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
  width: 10px;
  margin: 0 2px;
  background-color: Blue;
  border-radius:80%;
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
<section class="container">
       <div class="box">
         <h1> Welcome to  Sabbir's  Website </h1>
         <h3> ~`Student~`  ~`Learner~`  ~`Developer~` </h3>


<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="sabbir9.png" style="width:50%">
  <div class="text">SABBIR</div>






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
<p> Hello everyone! I'm Sabbir Hossain. I am from Bangladesh. I am a student,learner and developer.Here is my facebook link. You may contact me on facebook if you need.Thank you! </p>
         <a class="btn" href="https://www.facebook.com/profile.php?id=100015458081029"> My Facebook </a>
       </div>
       
       </div>
     </section>
     <section class="container"> 
       <div class="box"> <img class="img" src="sabbir10.png"> 
        <a class="btn" href=""> <b>WhatsApp:01891873630 </b>   </a>

        <br/>
       
       </div>
       <div class="box"> 
        <h1> Dream </h1>
        <h3> I want to be a professional businessman and entrepreneur  </h3>
        <p> Now, I am studying at a reputed college in Bangladesh. I have a dream to be a business magnet. After completing my study,I will start to fulfill my dream successful. </p>
            <p>Here is my instagram id.You may contact me here if you need.You may also follow me.Thank you!</p>
     
         
         
         <a class="btn" href="https://www.instagram.com/shossainbd303/"> My Instagram  </a>
       </div>
     </section>
     <section>
        <div class="itm"> 
         <h3 class="bom"> Contact </h3>
         <p> 01715167515  or   01891873630 </p>
        </div> 
        
      
     </section>
     
 
                      
</body>
</html> 

    
