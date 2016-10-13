# sushi-restaurant
CSS practice for NYU Class.
<!doctype html>
<html>
<head>
	<title>Brooklyn Eats: Matsu</title>

<style type="text/css" media="screen">

body {   
	color: #333;
    font-size: 16px;
    font-family: Arial, Helvetica, sans-serif;
	background: #999;
}

#wrapper {
    position: relative;
    width: 900px;
    max-width: 900px;
    background-color: #fff;
    margin: 0 auto 0 auto;
}
/*Photo of Brooklyn street*/
#brooklyn {
		float: right;
		height: 19px;
		width: 28px;
		padding: 5px 280px 35px 0;
}

p { 
	margin: 0 0 12px 0;
	line-height: 1.4em;
	font-family: Arial, Helvetica, sans-serif;
	font-size: 16px;

}

.nav {
    list-style: none;
    right:0;
    top:60px; 
	display: flex;
	flex: 1;
	background-color: #f0dfb4;
}

.nav li { 
    display: inline-block;
    margin-right: 10px;
}
.nav a {
    color: #333;
    text-decoration: none;
    padding: 4px;
    display: block;
    background-color: #f0dfb4
}

.nav a:hover {
  color: #fff; 
  background-color: #600; 
}

/*Box-out on cost, cuisine and region*/
#info {
	padding: 30px 0 30px 15px;
	position: absolute;  
  	border-radius: 0 10px 10px 0;
  	top: 200px; 
  	left: 0px; 
  	width: 160px; 
  	text-align: left;
  	background-color: #F0DFB4; 
  	border: 1px solid #600; 
  	box-shadow: 5px 5px 5px #ddd; 
}

#info th {
    text-align: left;
}

#info ul {
  list-style: none; 
  margin: 1em; 
  padding: 0;
}

.rating1 {
	text-align: justify;
	font-family: 'Oswald', sans-serif;
	font-size: 14px;
	color: #111;
}

.rating2 {
	text-align: left;
	font-family: Arial, Helvetica, sans-serif;
	margin-top: 15px;
	padding-top: 5px;
	font-size: 14px;
	color: #111;
}

article {
  margin: 0 20px 10px 200px;
}

blockquote  {
  	float: right; 
  	width: 40%;
  	padding: 16px; 
  	font-size: 20px; 
	border-top: 3px solid #600;
	border-bottom: 3px solid #600;
}

article img {
    float:  right;
}

h1, h2 {
  color: #600;
   margin-top: 20px;
   margin-left: 20px;
}
/*headline, subtitle*/
#title {
	font-family: 'Oswald', sans-serif;
	font-size: 40px;
	    -webkit-margin-before: 0.67em;
    -webkit-margin-after: 0.67em;
    -webkit-margin-start: 10px;
    -webkit-margin-end: 0px;
	letter-spacing: 1px;
}

#deck {
	font-size: 20px;
	color: #999;
	font-family: 'Roboto', sans-serif;
	padding: 45px 30px 10px 0;
	letter-spacing: .2em;
    font-size: 18px;
}

/*tagline description of restaurant*/
.summary {
  font-size: 16px; 
  border-bottom: 1px dotted #600;
  margin-left: 10px;
}

header {
  height:140px; 
}

header h1, header h2 {
    position: absolute;
    top: 15px;
}
header h2 {
    top: 50px;

}
h2 {
	display: block;
	font-size: 24px;
	font-weight: bold;
	font-family: 'Oswald', sans-serif;
	    -webkit-margin-before: 0.53em;
    -webkit-margin-after: 0.83em;
    -webkit-margin-start: 10px;
    -webkit-margin-end: 0px;
    padding-top: 0px;
	
}

#address {
	list-style: none;
}
.praise {
	font-family: 'Roboto', sans-serif;
}

#review {
	margin-left: 10px;
}

footer {
	font-family: Arial, Helvetica, sans-serif;
	font-size: 14px;
	background-color: #fff;
	margin: auto;
	padding: 20px;
	margin: 20px;

}

</style> 
<link href="https://fonts.googleapis.com/css?family=Oswald" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">


</head>

<body>
<div id="wrapper">

	<nav>
		<ul class="nav">
	<li><a href="#">Cuisines</a></li>
	<li><a href="#">Chefs</a></li>
	<li><a href="#">Reviews</a></li>
	<li><a href="#">Delivery</a></li>
		</ul>
	</nav>

    <header>
	    <h1 id="title">Brooklyn Eats</h1>
	    <h2 id="deck">A Guide to Fine North Brooklyn Dining</h2>
	<div id="brooklyn"><img src="http://brianwise.net/wp-content/uploads/2015/11/joralemon-street-brooklyn.jpeg" alt="brooklyn" width="300" height="200"><div>
    </header>
    
	<article>
		<h2>Matsu</h2>
		<p>
<p class="summary"><strong>Bottom Line: </strong>Friendly, cozy, and oh so tasty</p>
<div id="info">
		<table>
			<tbody>
				<tr>
					<th class="rating1">Cuisine:</th>
					<td class="rating2">Japanese</td>
				</tr>
				<tr>
					<th class="rating1">Cost:</th>
					<td class="rating2">$$ - $$$</td>
				</tr>
				<tr>
					<th class="rating1">Region:</th>
					<td class="rating2">Park Slope</td>
				</tr>
			</tbody>
		</table>
		<ul id ="address">
			<li class="rating1">Matsu</li>
			<li class="rating1">1258 Flatbush Avenue</li>
			<li class="rating1">Brooklyn, NY 11238</li>
			<li class="rating1"><a href="#">Map</a> | <a href="#">Directions</a></li>
			<li class="rating1">(718) 767-1111</li>
			<li class="rating1"><a href="#">Web site</a></li>
		</ul>
</div>
<div id="review">
		<p>If there's one <a href="#">Asian cuisine</a> we truly love, it's sushi (although dim sum comes a close second). Prepared correctly, sushi can be a work of sublime art to both the eyes and the tongue. There's nothing quite like the taste of a fresh piece of suzuki (sea bass) or salmon artfully combined with special rice and a hint of wasabi (Japanese horseradish). "Fresh fish in Brooklyn?" we hear you asking. Absolutely. There are several very good sushi restaurants in the area, but for our money, Matsu is at the head of the pack. <em>It's so good, it beats out most of the Brooklyn sushi places we've tried.</em></p>

		<blockquote> <span class="praise">It's so good, it beats out most of the Brooklyn sushi places we've tried.</span></blockquote>

		<p>On a recent visit, we checked out the specials and were delighted to see that escolar, a mild white fish, was available. The toro, on the other had, was sold out, so we had to put it off until another time. We ordered a sampling of nigiri (escolar, alabacore, suzuki, and smoked salmon), a couple of maki rolls, two bowls of miso soup, and gyoza (small dumplings steamed and then pan-fried). While we waited, we took a look around at the small dining room, which can seat about 30 people without making them feel at all cramped; another ten or so seats are available at the sushi bar along one side of the dining room. Between the intimate feel of the room and its subtle decoration, we felt comfortable right away.</p>

		<p>The miso came out first, and was quite good, hot and pungent, perfect for a cool evening or whenever you're feeling under the weather. The gyoza followed soon thereafter, and were nicely prepared, warm and soft without being too greasy or mushy. The meal really got underway, though, when our sushi arrived. Each nigiri portion featured a generous slice of fish on top of perfectly-sized rice ball, hand-made and formed by the chefs. One of the keys to nigiri is the wasabi smear between the rice and fish: too much, and it overpowers everything else; too little, and the tastes feel bland. Happily, every one of our nigiri pieces had exactly the right amount of wasabi to add a subtle zing to every mouthful. The maki rolls were also nicely prepared, with an appropriate balance of ingredients.</p>

		<img src="img/sushi-a.jpg">

		<p>For dessert, we decided to order strawberry mochi balls, which are small spheres of ice cream surrounded by a glutinous rice coating. Our order came out with the balls cut in half, which was a particularly nice touch since it made the dish easier to share. We ended the evening with some sweet sake recommended to us by our server - a perfect note to close out the meal.</p>

		<p>Husband-and-wife team Scott and Brenda Kim, who opened up Matsu in late 2000, are there almost every day of the week and help make every customer feel at home. When we returned on a later night, we were immediately recognized and greeted almost like family. The servers generally keep a close eye on the tables, which is one benefit of the limited seating. Scott is often behind the sushi bar, tending to orders himself, or else in the kitchen doing the same. Brenda, as hostess, oversees the servers and seating with efficiency and charm.</p>

		<p>If you're looking for a good Japanese experience but can't foot the bill for a flight to Tokyo, then Matsu is an excellent backup plan. We'll be back again soon.</p></div>
	</article>
	<footer><address>Brooklyn Eats covers the dining scene in New York City's hippest, most vibrant borough. <a href="mailto:brooklyneats@gmail.com" title="Contact us">E-mail us</a> with your tips and feedback.</address></footer></div>
</body>
</html>
