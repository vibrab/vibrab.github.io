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

body {
  font-family: Arial, Helvetica, sans-serif;
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

/* Clear floats after the columns */
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
  <h3>THE TOP 5 </h3>
    <ol>
      <li><a href="#">CruchWrap Supreme</a></li>
	    <br>
      <li><a href="#">Nacho Fries</a></li>
	    <br>
      <li><a href="#">Cantina Chicken Wrap</a></li>
	    <br>
      <li><a href="#">Mexican Pizaa</a></li>
	    <br>
      <li><a href="#">Baja Blast</a></li>

    </ol>
  </nav>
  
  <article>
    <h1>London</h1>
    <p></p>
    <p></p>
    <p></p>
    <p></p>
    <p></p>
	  
  </article>
</section>



</body>
</html>

