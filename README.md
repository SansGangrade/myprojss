<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;

}
h2{
	margin: 0;
}

/*#first {
	list-style-type: none;
	padding: 0;
	background-image: url("ff.jpg");
	background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;*/



}

body {
  font-family: Arial, Helvetica, sans-serif;
}
#sec {
	background-color: lightpink;
	
}

/* Style the header */
header , h2 {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
  
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: ivory;
  background-image: url("ff.jpg");
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;



}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>
<div>
  <img src="gif.gif" alt="India Gif" width="1500" height="300">
</div>

<h2 >INDIA : Land of Cultural Diversity </h2>

    

<p><b>India</b> (Hindi: Bhārat), officially the Republic of India (Hindi: Bhārat Gaṇarājya),is a country in South Asia. It is the second-most populous country, the seventh-largest country by land area, and the most populous democracy in the world. Bounded by the Indian Ocean on the south, the Arabian Sea on the southwest, and the Bay of Bengal on the southeast, it shares land borders with Pakistan to the west; China, Nepal, and Bhutan to the north; and Bangladesh and Myanmar to the east. In the Indian Ocean, India is in the vicinity of Sri Lanka and the Maldives; its Andaman and Nicobar Islands share a maritime border with Thailand and Indonesia.</p>
<img src="f1.jpg" alt="indian culture" width="300" height="300">

<img src="f3.jpg" alt="indian culture" width="300" height="300">
	<img src="p1.jpg" alt="indian culture" width="300" height="300">
	<img src="p5.jpg" alt="indian culture" width="300" height="300">
	<img src="f2.jpg" alt="indian culture" width="280" height="300">
	


<header >  <h2>INCREDIBLE INDIA</h2>
</header>

<section>
  <nav>
    <ul>
      <li><a href="https://knowindia.gov.in/profile/the-union-and-its-territory.php" target="_blank">Union Territories</a></li>
      <li><a href="https://www.india.gov.in/india-glance/states-india" target="_blank">States</a></li>
      <li><a href="http://delhitourism.gov.in/delhitourism/index.jsp" target="_blank">Delhi,Capital of India</a></li>
      <li><a href="http://adaniel.tripod.com/cities.htm" target="_blank">Cities</a></li>
      <li><a href="https://en.wikipedia.org/wiki/List_of_districts_in_India#:~:text=In%20some%20cases%20districts%20are,the%202001%20Census%20of%20India." target="_blank">Districts</a></li>
      <li><a href="https://lgdirectory.gov.in/" target="_blank">Gram Panchayat</a></li>
    </ul>
  </nav>


  
  <article id="sec">
    <h1>Culture of India</h1>
     
    
    <p>India is a diverse country, a fact that is visibly prominent in its people, culture and climate. From the eternal snows of the Himalayas to the cultivated peninsula of far South, from the deserts of the West to the humid deltas of the East, from the dry heat and cold of the Central Plateau to the cool forest foothills, Indian lifestyles clearly glorify the geography.

The food, clothing and habits of an Indian differ in accordance to the place of origin.

</p>
    <p>
The Indian culture varies like its vast geography. People speak in different languages, dress differently, follow different religions, eat different food but are of the same temperament. So whether it is a joyous occasion or a moment of grief, people participate whole-heartedly, feeling the happiness or pain. A festival or a celebration is never constrained to a family or a home. The whole community or neighbourhood is involved in bringing liveliness to an occasion. Likewise, an Indian wedding is a celebration of union, not only of the bride and groom, but also of two families, maybe cultures or religion too! Similarly, in times of sorrow, neighbours and friends play an important part in easing out the grief.

</p>



  </article>
</section>

  
<footer>
  <p>Know More About INDIA</p>
  <p>Copyright &copy : Govt. Of India</p>

<!--<section id="first">	
	<p>
<button onclick="document.location='"https://www.india.gov.in/"'">About Us</button>
</p>
  	<p><a href="mailto:kriti2716@gmail.com">Send E-mail</a></p>
  	<p><a href="#">Contact Us</a></p>
  	<p><a href="#">Services</a></p>
</section>-->
</footer>

</body>
</html>
