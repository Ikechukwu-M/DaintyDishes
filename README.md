<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE-edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="css/bootstrap.css">
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="css/cwstyle.css">
	<title>Dainty Dishes</title>
</head>
<body>
<!-- JUMBOTRON STARTS HERE -->
		<div class="jumbotron">
	<div class="container-fluid">
			<div class="row">
			<div id="logo" class="col-md-3">
				<a href="index.html"><img src="images/foodlogo1.jpg" alt="Foodlogo"></a>
			</div>
			<div id="topbanner" class="col-md-9">
			<a href="index.html"><h1>DAINTY DISHES</h1></a>
			<p> It's not dainty <em><strong>if it is not Dainty's</strong></em></p>
			</div>
			</div>
		</div>
	</div>
	<!-- JUMBOTRON ENDS HERE -->

	<!-- NAVIGATION BAR STARTS HERE -->
	<nav class="navbar navbar-inverse">
		<div class="container">
			<div class="navbar-header">

			<!-- This is for the button for the navigation bar for the xs -->
				<button type="button" class="navbar-toggle collapsed" data-toggle="collapse"  data-target="#navbar" aria-extended="false" aria-controls="navbar">
					<span class="sr-only">Toggle Navigation</span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
				</button>
			<!-- The button ends here -->		
			</div>
			<div id="navbar" class="navbar-collapse collapse">
			<ul class="nav navbar-nav">
				<li class="active"><a href="index.html"><span class="glyphicon glyphicon-home"></span>Home</a></li>
				<li><a href="#"><span class="glyphicon glyphicon-info-sign" aria-hidden="true"></span>About</a></li>
				<li class="dropdown">
				<a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-extended="false"><span class="glyphicon glyphicon-list-alt Menu" aria-hidden="true"></span>Menu<span class="caret"></span></a>
					<ul class="dropdown-menu">
						<li><a href="breakfast.html">Breakfast</a></li>
						<li><a href="lunch.html">Lunch</a></li>
						<li><a href="dinner.html">Dinner</a></li>
						<li><a href="dessert.html">Desserts</a></li>
					</ul>
				</li>
				<li><a href="contactus.html"><span class="glyphicon glyphicon-envelope"></span> Contact Us</a></li>
			</ul>
			
			<form id="formcolor" class="form-inline navbar-right" role="form">
				<div class="form-group">
					<label for="username">Username:</label>
					<input type="username" class="form-control input-sm" id="username" placeholder="Username" name="">
				</div>
				<div class="form-group">
					<label for="Password">Password:</label>
					<input type="pwd" class="form-control input-sm" id="pwd" placeholder="Password" name="">
				</div>
				<div class="checkbox">
					<label id="font"><input type="checkbox" name="">Remember me</label>
				</div>
				<button class="btn btn-info" type="login">Login</button>
			</form>
			</div>
		</div>
	</nav>
<!-- END OF NAVIGATION BAR -->

<!-- NOW FOR THE PAGER -->
<ul class="pager">
	<li class="next"><a href="breakfast.html">Next</a></li>
</ul>
<!-- PAGER ENDS HERE -->

<!-- CAROUSEL SLIDES -->
<div id="jumbo">
<div class="jumbotron">
<div class="container">
  <br>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="images/view/restview.jpg" alt="Restaurant" width="1180px" height="300px" class="img-responsive">
      </div>

      <div class="item">
        <img src="images/view/Genesis.png" alt="Fastfood" width="1180px" height="300px" class="img-responsive">>
      </div>
    
      <div class="item">
        <img src="images/view/Background.jpg" alt="Exclusive" width="1180px" height="300px" class="img-responsive">>
      </div>

      <div class="item">
        <img src="images/view/Nkoyo.jpg" alt="Chinese" width="1180px" height="300px" class="img-responsive">>
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>
</div>
</div>


<!-- MENU TILES -->
<div class="container">
	<div class="row">
		<div class="col-md-4">
			<a href="breakfast.html"><div id="breakfast"><span>Breakfast</span></div></a>
		</div>

		<div class="col-md-4">
			<a href="lunch.html"><div id="lunch"><span>Lunch</span></div></a>
		</div>

		<div class="col-md-4">
			<a href="dinner.html" data-toggle="tooltip" data-placement="bottom" title="Dinner"><div id="dinner"><span>Dinner</span></div></a>
		</div>
	</div>
</div>
<!-- MENU TILES END HERE -->



<!-- HOW ABOUT SOME PAGINATION -->
<ul class="pagination">
    <li class="active"><a href="index.html">1</a></li>
    <li><a href="breakfast.html">2</a></li>
    <li><a href="lunch.html">3</a></li>
    <li><a href="dinner.html">4</a></li>
    <li><a href="dessert.html">5</a></li>
    <li><a href="contactus.html">6</a></li>
    <li><a href="jamiu.html">7</a></li>
  </ul>
  <!-- END OF PAGINATION -->

<!-- FOOTER BEGINS HERE -->
<footer class="panel-footer">
    <div class="container">
      <div class="row">
        <section id="hours" class="col-sm-4">
          <span>Hours:</span><br>
          Mon-Fri: 8:45am - 9:30pm<br>
          Sat: 8:45am - 2:30pm<br>
          Sunday Closed
          <hr class="visible-xs">
        </section>
        <section id="address" class="col-sm-4">
          <span>Address:</span><br>
          23 Lokongoma Road<br>
          Lokoja, Kogi State.
          <p>* Delivery area within 3-4 miles, with minimum order of #2,000 plus #300 charge for all deliveries.</p>
          <hr class="visible-xs">
        </section>
        <section id="testimonials" class="col-sm-4">
          <p>"They treat food here like an art, its an amazing experience all the time"</p>
          <p>"The food; amazing! The service; awesome! it doesn't get any better than this"</p>
        </section>
      </div>
      <div class="text-center">&copy; Copyright Dainty Dishes 2017</div>
    </div>
  </footer>



<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="js/jquery-2.1.4.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/script.js"></script>

</body>
</html>
