<!DOCTYPE html>
<html lang="en">
<head>
<title> THE TACOBELL REVIEW </title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Courier New, monospace;
}

 Style the header */
 
header {
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
  height: 400px; /* only for demonstration, should be removed */
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

! Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}


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

<h2>CSS Layout Float</h2>
<p>In this example, we have created a header, two columns/boxes and a footer. On smaller screens, the columns will stack on top of each other.</p>
<p>Resize the browser window to see the responsive effect (you will learn more about this in our next chapter - HTML Responsive.)</p>

<header>
  <h2>REVIEW</h2>
</header>

<section>
  <nav>
  <h3> 🔔 THE TOP 5 🌮 🌯</h3>
    <ol>
      <li><a href="https://www.tacobell.com/food/specialties/crunchwrap-supreme">CruchWrap Supreme</a></li>
	    <br>
      <li><a href="https://www.tacobell.com/food/deals-and-combos/nacho-fries">Nacho Fries</a></li>
	    <br>
      <li><a href="https://www.tacobell.com/food/deals-and-combos/cantina-chicken-burrito">Cantina Chicken Wrap</a></li>
	    <br>
      <li><a href="https://www.tacobell.com/food/specialties/mexican-pizza">Mexican Pizaa</a></li>
	    <br>
      <li><a href="https://www.tacobell.com/food/drinks/mtn-dew-baja-blast?store=026046">Baja Blast</a></li>

    </ol>
  </nav>
  
  <article>
<ol>  
    <h1>WHY</h1>
   <li> At first place is the <strong> Crunchwrap Supreme </strong>. The Crunch Wrap Supreme is a warm hexagonal wrap containg your protein of choice, veggies, and a crunchy tortilla within the wrap! This item is one of Taco Bell's tastiest items and can be eaten at all times of the day as there are breakfeast crunchwraps aswell.</li>	 												<imgsrc="https://www.simplyrecipes.com/thmb/rbgbvhXHK03BzVmJcYdUuFL_jWw=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Simply-Recipes-Copycat-Crunchwrap-LEAD-3-2a25fc4f7e8f469c849c150f381eeefa.jpg" alt="Crunch wrap supreme"
<br>
   <li> At second would be the <srong>Nacho Fries</srong>. A limited time speciality and an unexpexted hit on the Taco Bell Menu, The Nacho Fries are crispy fries seasoned with "bold Mexican spices" and served with a side of nacho cheese sauce. This underrated item has become a fan favorite over a couple years, serving unique flavors that no other fast food offer. </li>
	<br>
   <li> At third would be the new and improved<strong> Cantina Chicken Burrito </srong>. Another limited time speciality, as it uses a unique slow roasted and flavorful chicken, veggies, and cheddar cheese. The burrito is also accompanied with a unique avacado verde salsa packet, that enhances the flavor profile of the burrito. </li>
	   <br>
   <li> At fourth would be the classic Mexican Pizza. A staple for the vegetaraian community for a long time and a unique fusion invention. The mexican pizza conatins Mexican pizza sauce, refried beans, protein, and veggies all sandwhihced between two crispy tortillas. </li>
	   <br>
   <li> Lastly, the infamous drink of Taco Bell, the <strong> Baja Blast</strong>. A strong, fizzy, and refreshing drink to wash down your meals. The Baja Blast is a lime flavoured Mountain Dew flavour, and its popularity has led to the making of its own slushees and even gelattos!   </li>
</ol>
	  
  </article>
  
s<imgsrc="https://www.simplyrecipes.com/thmb/rbgbvhXHK03BzVmJcYdUuFL_jWw=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Simply-Recipes-Copycat-Crunchwrap-LEAD-3-2a25fc4f7e8f469c849c150f381eeefa.jpg" alt="Crunch wrap supreme"

</section>






</body>
</html>

