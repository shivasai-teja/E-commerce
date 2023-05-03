# E-commerce
This code is for developing a basic e-commerce website using html&amp;css

#HTML Code

<!DOCTYPE html>
<html>
<head>
	<title>SST Sports</title>
	<link rel="stylesheet" type="text/css" href="Project.css">
</head>
<body>
	<div id="showcase">
		<header>
			<nav class="cf">
				<ul class="cf">
					<li>
						<a href="#showcase">SST Sports</a>
					</li>
					<li>
						<a href="#aboutus">About us</a>
					</li>
					<li>
						<a href="#indoor">Indoor</a>
					</li>
					<li>
						<a href="#outdoor">Outdoor</a>
					</li>
					<li>
						<a href="#history">History</a>
					</li>
				</ul>
				<a href="#" id="openup">SST Sports</a>
			</nav>
		</header>

		<div class="section-main container">
			<h1>SST Sports</h1>
			<h2> - Your best to visualize and enjoy playing different sports - </h2>
			<p class="lead hide-on-small">
			My sports is the best way to organize and enjoy the feel of playing and stepping into the world of virtual sports - and shop for the ones you want. Enjoy all the entertainment provided free and in anyplatform - MAC and Windows.
		</p>
	</div>
</div>
      <footer>
		<div class="container">
			<div class="footer-cols">
				<ul>
					<li>
						Shop & Play
					</li>
					<li>
						<a href="#">3D Sports</a>
					</li>
					<li>
						<a href="#">Arcade Sports</a>
					</li>
					<li>
						<a href="#">Virtual Reality</a>
					</li>
					<li>
						<a href="#">Merchandise</a>
					</li>
					<li>
						<a href="#">Gift cards</a>
					</li>
				</ul>
					<ul>
					<li>
						SST Sports Store
					</li>
					<li>
						<a href="#">Find a store</a>
					</li>
					<li>
						<a href="#">Today at SST Sports</a>
					</li>
					<li>
						<a href="#">Sports camp</a>
					</li>
					<li>
						<a href="#">Entertainment</a>
					</li>
					<li>
						<a href="#">Order Sports Items</a>
					</li>
				</ul>
				</ul>
					<ul>
					<li>
						Education and Business
					</li>
					<li>
						<a href="#">SST & Education</a>
					</li>
					<li>
						<a href="#">Shop for Courses</a>
					</li>
					<li>
						<a href="#">SST & Business</a>
					</li>
					<li>
						<a href="#">Shop for Business</a>
					</li>
					<li>
						<a href="#">Jobs</a>
					</li>
				</ul>
				</ul>
					<ul>
					<li>
						About SST
					</li>
					<li>
						<a href="#">Newsroom</a>
					</li>
					<li>
						<a href="#">SST Leadership</a>
					</li>
					<li>
						<a href="#">SST Blogs</a>
					</li>
					<li>
						<a href="#">Events</a>
					</li>
					<li>
						<a href="#">Contact SST </a>
					</li>
				</ul>
			</div>
			
		
		<div class="footer-bottom">
			Copyright &copy; 2023 ShivaSaiTeja
		</div>
	</footer>
</body>
</html>



#CSS Code

body{
	font-family: "PT Sans", sans-serif;
	background-color: #252529;
	margin: 0;
	color: #fff;
	line-height: 1;
}
a{
	text-decoration:none;
	color:#ccc;
}
#showcase{
	margin:0;
	padding:0;
	background:url('download2.jpg') no-repeat center/cover;
	width:100%;
	height: 150%; /* viewport-height */
	position: relative;
	overflow-y: hidden;

}
#showcase .container{
	margin-top: 20%;
      margin-bottom: 10%;

}
#showcase h1{
	font-size: 4rem; /* rem-root element font size */
}
#showcase h2{
	font-size:2rem ;
      margin-bottom: 10%;
}
#showcase p{
	font-family: Times New Roman;

}

nav{
	height: 40px;
	width: 100%;
	background-color: #333;
	color:rgb(51,34,34);
	position: fixed;
}
nav ul{
	margin: 0;
	padding: 0;
}
nav li{
	display: inline;
	float: left;
}
nav a{
	display: inline-block;
	width: 100px;
	text-align: center;
	text-decoration: none;
	padding: 10px 0; /* top-bottom/ left-right */
	color:#eee;
}

nav li:hover{
	background-color: #444;
}
.container{
	max-width: 1180px;
	text-align: center;
	margin: 0 auto;
	padding: 0 3rem;
}
.lead{
	font-size: 3rem;
}
footer .footer-cols{
	display: grid;
	grid-gap: 20px;
	grid-template-columns: repeat(4,1fr);
	padding: 2rem;
	text-align: left;
	font-size: 14px;
}
footer .footer-cols ul{
	list-style: none;

}
footer .footer-cols ul li:first-child{
	font-size: 1.2rem;
	padding-bottom: 0.5rem;
	border-bottom: #444 solid 2px;
	margin-bottom: 1rem;
}
footer .footer-bottom{
	background-color:#333;
	padding:1rem;
	text-align:center;
}
