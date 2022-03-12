<!DOCTYPE html>
<html lang="en-US">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>{{ page.title }}</title>
	<meta name="keywords" content="{{ page.keywords }}">
	<meta name="description" content="{{ page.description }}">
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
<header id="header" class="over">

	<div class="container">
		
		<!-- mobile menu toggle -->
		<button class="menu-toggle">
			<span></span>
			<span></span>
			<span></span>
		</button>
		
		<!-- main menu -->
		<nav class="horizontal-menu scrollspy">
			<ul>
				<li><a href="#hero">个人主页</a></li>
				<li><a href="#about">关于我</a></li>
				<li><a href="#services">服务</a></li>
				<li><a href="#resume">个人经历</a></li>
				<li><a href="#works">博客</a></li>
				<li><a href="#contact">联系我</a></li>
			</ul>
		</nav>

	</div>
	
	<!-- mobile menu -->
	<nav class="mobile-menu scrollspy">
		<ul>
			<li><a href="#hero">个人主页</a></li>
			<li><a href="#about">关于我</a></li>
			<li><a href="#services">服务</a></li>
			<li><a href="#resume">个人经历</a></li>
			<li><a href="#works">博客</a></li>
			<li><a href="#contact">联系我</a></li>
		</ul>
	</nav>

</header>

<!-- section hero -->
<section id="hero" class="hero" data-stellar-background-ratio="0.5">
		
	<div class="intro">

		<div class="container">
			
			<!-- parallax layers -->
			<div class="parallax" data-relative-input="true">
				
				<!-- name -->
				<h1 class="name layer" data-depth="0.5">刘凯</h1>
				
				<!-- job -->
				<span class="job layer" data-depth="0.6">高级软件工程师</span>
				
				<!-- social profiles -->
				<ul class="social-profiles layer" data-depth="0.4">
					<li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
					<li><a href="#"><i class="fab fa-twitter"></i></a></li>
					<li><a href="#"><i class="fab fa-instagram"></i></a></li>
				</ul>
				
				<!-- picture -->
				<div class="image">
					<div class="layer" data-depth="0.7">
						<img src="static/picture/talib-1.jpg" alt="talib">
					</div>
				</div>

			</div>

		</div>

	</div>
	
	<!-- scroll down icon -->
	<a href="#about" class="scroll-down-icon">
		<i class="fas fa-chevron-down scroll-down"></i>
	</a>
	
	<div class="mask"></div>
</section>

<!-- section about -->
<section id="about" class="about with-line">

	<div class="container">
		
		<!-- section header -->
		<div class="section-header">
			<span class="back-text">About Me</span>
			<h2>个人网站</h2>
			<span class="line"></span>
		</div>

		<div class="row">
			
			<!-- picture -->
			<div class="col-sm-4">
				<img src="static/picture/talib-2.jpg" alt="talib">
			</div>
			
			<!-- about text -->
			<div class="col-sm-4">
				<h4 class="title mb-4">我是刘凯。</h4>
				<p class="mb-4">欢迎访问我的个人网站。</p>
				<!-- <img src="static/picture/signature.png" alt="signature"> -->
			</div>
			
			<!-- skill progress bars -->
			<div class="col-sm-4">

				<h4 class="title">职业技能</h4>

				<div class="skill-item">
					<div class="skill-info clearfix">
						<span class="title float-left">JavaScript</span>
						<span class="percent float-right">90%</span>
					</div>
					<div class="progress">
						<div class="progress-bar" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100">
						</div>
					</div>
				</div>

				<div class="skill-item">
					<div class="skill-info clearfix">
						<span class="title float-left">PHP</span>
						<span class="percent float-right">95%</span>
					</div>
					<div class="progress">
						<div class="progress-bar" role="progressbar" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100">
						</div>
					</div>
				</div>

				<div class="skill-item">
					<div class="skill-info clearfix">
						<span class="title float-left">HTML</span>
						<span class="percent float-right">70%</span>
					</div>
					<div class="progress">
						<div class="progress-bar" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100">
						</div>
					</div>
				</div>

				<div class="skill-item">
					<div class="skill-info clearfix">
						<span class="title float-left">CSS</span>
						<span class="percent float-right">92%</span>
					</div>
					<div class="progress">
						<div class="progress-bar" role="progressbar" aria-valuenow="92" aria-valuemin="0" aria-valuemax="100">
						</div>
					</div>
				</div>

			</div>

		</div>

	</div>
	
</section>

<!-- section services -->
<section id="services" class="services with-line">

	<div class="container">
		
		<!-- section header -->
		<div class="section-header">
			<span class="back-text">Services</span>
			<h2>What Can I Do</h2>
			<span class="line"></span>
		</div>
		
		<!-- carousel wrapper -->
		<div class="row services-wrapper">
			
			<div class="col-sm-4">
				
				<div class="service-box box-shadow">
					<i class="icon-camera"></i>
					<h4 class="title">Photography</h4>
					<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
				</div>

			</div>

			<div class="col-sm-4">
				
				<div class="service-box box-shadow">
					<i class="icon-puzzle"></i>
					<h4 class="title">Illustration</h4>
					<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
				</div>

			</div>

			<div class="col-sm-4">
				
				<div class="service-box box-shadow">
					<i class="icon-frame"></i>
					<h4 class="title">Product Design</h4>
					<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
				</div>

			</div>

			<div class="col-sm-4">
				
				<div class="service-box box-shadow">
					<i class="icon-screen-smartphone"></i>
					<h4 class="title">Mobile Development</h4>
					<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
				</div>

			</div>

			<div class="col-sm-4">
				
				<div class="service-box box-shadow">
					<i class="icon-globe-alt"></i>
					<h4 class="title">Web Development</h4>
					<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
				</div>

			</div>

		</div>

	</div>
	
</section>

<!-- section testimonials carousel -->
<section class="dark testimonials" data-stellar-background-ratio="0.5">
	
	<div class="container">
		
		<!-- carousel wrapper -->
		<div class="testimonials-wrapper">
			
			<!-- testimonial item -->
			<div class="testimonial-item">
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ut condimentum lacus. Nullam est urna, maximus eget maximus eu, sodales et tellus.</p>
				<img src="static/picture/customer-1.jpg" alt="John Doe">
				<h4 class="title">John Doe</h4>
			</div>
			
			<!-- testimonial item -->
			<div class="testimonial-item">
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ut condimentum lacus. Nullam est urna, maximus eget maximus eu, sodales et tellus.</p>
				<img src="static/picture/customer-1.jpg" alt="John Doe">
				<h4 class="title">John Doe</h4>
			</div>
			
			<!-- testimonial item -->
			<div class="testimonial-item">
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ut condimentum lacus. Nullam est urna, maximus eget maximus eu, sodales et tellus.</p>
				<img src="static/picture/customer-1.jpg" alt="John Doe">
				<h4 class="title">John Doe</h4>
			</div>

		</div>

	</div>

	<div class="mask"></div>

</section>

<!-- section timeline -->
<section id="resume" class="resume with-line">

	<div class="container">
		
		<!-- section header -->
		<div class="section-header">
			<span class="back-text">Resume</span>
			<h2>个人经历</h2>
			<span class="line"></span>
		</div>
		
		<!-- timeline wrapper -->
		<div class="timeline">

			<!-- timeline left -->
			<div class="timeline-container left wow fadeIn">
				<div class="content box-shadow">
					<span class="time">2022</span>
					<h4 class="title">省二等奖</h4>
					<p>山西省“五小”创新大赛二等奖。</p>
				</div>
			</div>

			<!-- timeline right -->
			<div class="timeline-container right wow fadeIn">
				<div class="content box-shadow">
					<span class="time">2021</span>
					<h4 class="title">工人先锋号</h4>
					<p>临汾市“工人先锋号”（全市共30个）。</p>
				</div>
			</div>

			<!-- timeline left -->
			<div class="timeline-container left wow fadeIn">
				<div class="content box-shadow">
					<span class="time">2021</span>
					<h4 class="title">优胜奖</h4>
					<p>第八届“创青春”临汾青年创新创业大赛优胜奖。</p>
				</div>
			</div>

			<!-- timeline right -->
			<div class="timeline-container right wow fadeIn">
				<div class="content box-shadow">
					<span class="time">2020</span>
					<h4 class="title">优秀奖</h4>
					<p>“创客中国”临汾市中小企业创新创业大赛优秀奖。</p>
				</div>
			</div>

			<!-- main line -->
			<span class="line"></span>

		</div>

<!-- 		<div class="more-button text-center">
			<a href="#" class="btn btn-outline">下载简历</a>
		</div> -->

	</div>
	
</section>

{{ content }} 

<!-- section clients logo carousel -->
<section class="dark clients" data-stellar-background-ratio="0.5">

	<!-- fix validator issue -->
	<h2 class="hidden">Clients</h2>
	
	<div class="container">
		
		<!-- carousel wrapper -->
		<div class="clients-wrapper wow slideInRight">
			
			<!-- client item -->
			<div class="client-item">
				<a href="#">
					<img src="static/picture/client-1.png" alt="airbnb">
				</a>
			</div>
			
			<!-- client item -->
			<div class="client-item">
				<a href="#">
					<img src="static/picture/client-2.png" alt="business-insider">
				</a>
			</div>
			
			<!-- client item -->
			<div class="client-item">
				<a href="#">
					<img src="static/picture/client-3.png" alt="airbnb">
				</a>
			</div>
			
			<!-- client item -->
			<div class="client-item">
				<a href="#">
					<img src="static/picture/client-4.png" alt="business-insider">
				</a>
			</div>

			<!-- client item -->
			<div class="client-item">
				<a href="#">
					<img src="static/picture/client-5.png" alt="airbnb">
				</a>
			</div>
			
			<!-- client item -->
			<div class="client-item">
				<a href="#">
					<img src="static/picture/client-2.png" alt="business-insider">
				</a>
			</div>

		</div>

	</div>

	<div class="mask"></div>

</section>

<!-- section contact -->
<section id="contact" class="with-line">

	<div class="container">
		
		<!-- section header -->
		<div class="section-header">
			<span class="back-text">Contact</span>
			<h2>网站留言</h2>
			<span class="line"></span>
		</div>
			
		<div class="row">

			<!-- column with offset -->
			<div class="col-md-6 offset-md-3">

				<!-- Contact Form -->
				<form id="contact-form" class="contact-form" method="post" action="form/contact.php">
					
					<div class="messages"></div>

					<!-- Name input -->
					<div class="form-group">
						<input type="text" class="form-control" name="InputName" id="InputName" placeholder="姓名" required="required" data-error="请输入你的名字">
						<div class="help-block with-errors"></div>
					</div>

					<!-- Email input -->
					<div class="form-group">
						<input type="text" class="form-control" id="InputEmail" name="InputEmail" placeholder="电话" required="required" data-error="请输入手机号">
						<div class="help-block with-errors"></div>
					</div>			

					<!-- Message textarea -->
					<div class="form-group">
						<textarea name="InputMessage" id="InputMessage" class="form-control" rows="7" placeholder="留言内容" required="required" data-error="请输入留言内容"></textarea>
						<div class="help-block with-errors"></div>
					</div>

					<button type="button" name="submit" id="submit" value="Submit" class="btn btn-default btn-full">提交</button><!-- Send Button -->

				</form>
				<!-- Contact Form end -->

			</div>
			<!-- end column -->

		</div>

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