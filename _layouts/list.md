<!DOCTYPE html>
<html lang="en-US">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Talib - One Page Parallax Template for Personal & Agency</title>
	<meta name="description" content="Talib - One Page Parallax Template for Personal & Agency">
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">

	<!-- STYLESHEETS -->
	<link rel="stylesheet" href="static/css/bootstrap.min.css" type="text/css" media="all">
	<link rel="stylesheet" href="static/css/fontawesome-all.min.css" type="text/css" media="all">
	<link rel="stylesheet" href="static/css/simple-line-icons.css" type="text/css" media="all">
	<link rel="stylesheet" href="static/css/slick.css" type="text/css" media="all">
	<link rel="stylesheet" href="static/css/magnific-popup.css" type="text/css" media="all">
	<link rel="stylesheet" href="static/css/animate.css" type="text/css" media="all">
	<link rel="stylesheet" href="static/css/style.css" type="text/css" media="all">

	<!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->

</head>

<body>

<!-- site header -->
<header id="header" class="static with-logo">

	<div class="container">

		<div class="d-flex align-items-center pt-2 pb-2 d-lg-none">

			<!-- <a href="agency.html" class="navbar-brand"><img src="static/picture/logo.png" alt="talib"></a> -->
			
			<!-- mobile menu toggle -->
			<button class="ml-auto menu-toggle">
				<span></span>
				<span></span>
				<span></span>
			</button>

		</div>
		
		<!-- main menu -->
		<nav class="horizontal-menu scrollspy d-flex align-items-center">
			<a href="index.html" class="navbar-brand"><img src="static/picture/logo.png" alt="talib"></a>
			<ul class="ml-auto">
				<li><a href="agency.html#hero">Home</a></li>
				<li><a href="agency.html#services">Services</a></li>
				<li><a href="agency.html#team">Team</a></li>
				<li><a href="agency.html#works">Works</a></li>
				<li><a href="agency.html#price">Pricing</a></li>
				<li><a href="agency.html#contact">Contact</a></li>
			</ul>
			<ul class="social-profiles">
				<li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
				<li><a href="#"><i class="fab fa-twitter"></i></a></li>
				<li><a href="#"><i class="fab fa-instagram"></i></a></li>
			</ul>
		</nav>

	</div>
	
	<!-- mobile menu -->
	<nav class="mobile-menu scrollspy">
		<ul>
			<li><a href="agency.html#hero">Home</a></li>
			<li><a href="agency.html#services">Services</a></li>
			<li><a href="agency.html#team">Team</a></li>
			<li><a href="agency.html#works">Works</a></li>
			<li><a href="agency.html#price">Pricing</a></li>
			<li><a href="agency.html#contact">Contact</a></li>
		</ul>
	</nav>

</header>

<section class="page-header">
	<!-- section header -->
	<div class="section-header">
		<span class="back-text">Portfolio</span>
		<h2>Recent Works</h2>
		<span class="line"></span>
	</div>
</section>

<!-- section portfolio -->
<section id="works" class="portfolio with-line">

	<div class="container">
		
		<!-- portfolio filter (desktop) -->
		<ul class="portfolio-filter">
			<li class="current" data-filter=""><a href="/blog/">All</a></li>
			{% for category in site.categories %}
			<li data-filter=""><a href="{{ category | first }}/">{{ category | first }}</a></li>
			{% endfor %}
		</ul>
		
		<!-- portfolio filter (mobile) -->
		<select class="portfolio-filter-mobile">
			<option value="*"><a href="/blog/">All</a></option>
			{% for category in site.categories %}
			<option value=""><a href="{{ category | first }}/">{{ category | first }}</a></option>
			{% endfor %}
		</select>
		
		<!-- portolio wrapper -->
		<div class="row portfolio-wrapper wow slideInUp">
			{{ content }}
		</div>
		
	
		{% if paginator.total_pages > 1 %}
		<!-- pagination -->
		<nav class="pagination-outer">
			<ul class="pagination justify-content-center">
				<!-- 分页代码 -->
				{% if paginator.previous_page %}
				<li class="page-item">
					<a class="page-link" href="{{ paginator.previous_page_path }}" aria-label="Previous">
						<span aria-hidden="true">&laquo;</span>
						<span class="sr-only">Previous</span>
					</a>
				</li>
				{% else %}
				<li class="page-item">
					<a class="page-link disabled" href="javascript:;" aria-label="Previous">
						<span aria-hidden="true">&laquo;</span>
						<span class="sr-only">Previous</span>
					</a>
				</li>
				{% endif %}

				{% if paginator.next_page %}
				<li class="page-item">
					<a class="page-link" href="{{ paginator.next_page_path }}" aria-label="Next">
						<span aria-hidden="true">&raquo;</span>
						<span class="sr-only">Next</span>
					</a>
				</li>
				{% else %}
				<li class="page-item">
					<a class="page-link disabled" href="javascript:;" aria-label="Next">
						<span aria-hidden="true">&raquo;</span>
						<span class="sr-only">Next</span>
					</a>
				</li>
				{% endif %}
			</ul>
		</nav>
		{% endif %}
	</div>
	
</section>



<!-- site footer -->
<footer>
	<div class="container d-md-flex align-items-center justify-content-between">
		
		<!-- copyright text -->
		<span class="copyright">Copyright &copy; 2022.Company name All rights reserved.</span>
		
		<!-- social icons -->
		<ul class="social-profiles">
			<li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
			<li><a href="#"><i class="fab fa-twitter"></i></a></li>
			<li><a href="#"><i class="fab fa-instagram"></i></a></li>
		</ul>

	</div>
</footer>

<!-- Go to top button -->
<a href="javascript:" id="return-to-top"><i class="fa fa-chevron-up"></i></a>

<!-- SCRIPTS -->

<!-- jQuery -->
<script src="static/js/jquery-1.12.3.min.js"></script>
<!-- jQuery easing -->
<script src="static/js/jquery.easing.min.js"></script>
<!-- Popper -->
<script src="static/js/popper.min.js"></script>
<!-- Bootstrap -->
<script src="static/js/bootstrap.min.js"></script>
<!-- jPreloader -->
<script src="static/js/jpreloader.min.js"></script>
<!-- Waypoints JS -->
<script src="static/js/jquery.waypoints.min.js"></script>
<!-- Counterup JS -->
<script src="static/js/jquery.counterup.min.js"></script>
<!-- Stellar (parallax) -->
<script src="static/js/jquery.stellar.js"></script>
<!-- Magnific Popup -->
<script src="static/js/jquery.magnific-popup.min.js"></script>
<!-- Isotope (filtered portfolio) -->
<script src="static/js/isotope.pkgd.min.js"></script>
<!-- Wow JS -->
<script src="static/js/wow.min.js"></script>
<!-- Flat Surface Shader JS -->
<script src="static/js/fss.min.js"></script>
<!-- Particles JS -->
<script src="static/js/particles.min.js"></script>
<script src="static/js/particles-config.js"></script>
<!-- Parallax JS -->
<script src="static/js/parallax.min.js"></script>
<!-- Slick carousel -->
<script src="static/js/slick.min.js"></script>
<!-- Bootstrap Validator -->
<script src="static/js/validator.js"></script>
<!-- Contact form -->
<script src="static/js/contact.js"></script>
<!-- Talib Template JS -->
<script src="static/js/custom.js"></script>

<!-- END SCRIPTS -->

</body>
</html>