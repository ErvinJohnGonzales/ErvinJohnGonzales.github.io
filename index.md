<!--Coded by Ervin-->

<html>
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial=scale-1.0">
		<title>Coding@Ervin</title>
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css" crossorigin="anonymous">
		<link rel="stylesheet" href="style.css">
		<link href="https://fonts.googleapis.com/css?family=Source+Code+Pro:400,900|Source+Sans+Pro:300,900&display=swap" rel="stylesheet">
	</head>

	
	<body>
		
		<header>
			<div class="logo">
				<img src="L16.png" alt="">
			</div>
			<button class="nav-toggle" aria-label="toggle navigation">
				<span class="burger"></span>
			</button>
			<nav class="nav">
				<ul class="nav__list">
					<li class="nav__item"><a href="#home" class="nav__link">Home</a></li>
					<li class="nav__item"><a href="#services" class="nav__link">My Service</a></li>
					<li class="nav__item"><a href="#about" class="nav__link">About me</a></li>
					<li class="nav__item"><a href="#work" class="nav__link">My Work</a></li>
				</ul>
			</nav>
		</header>

		<section class="intro" id="home">
			<h1 class="section__title section__title--intro">
				Hi, I'm <strong>Ervin Gonzales</strong>
			</h1>
			<p class="section__subtitle section__subtitle--intro">Database Developer</p>
			<img src="ervin.jpg" alt="" class="intro__img">
		</section>
			
		<section class="my-services" id="services">
			<h2 class="section__title section__title--services">What I can do</h2>
			<div class="service">
				
				<div class="service">
					<h3>SQL</h3>
					<p>I have developed projects using SQL. Specifically, a relational database which I used to develop a student enrollment desktop application with queries and insert functions.</p>
				</div>	

				<div class="service">
					<h3>Web Design</h3>
					<p>I developed this portfolio website using HTML, CSS and JavaScript. I made a custom property to modify the colors and text sizes to fit my style. This website is self-hosted on my personal server.</p>
				</div>	

				<div class="service">
					<h3>Python</h3>
					<p>I created a student enrollment desktop appplication, with a working GUI and SQLite database. It's password protected and has a built-in payment function and a working subject selection screen. It can also accept and register new student information directly to the database.</p>
				</div>			
			
			</div>
			<a href="#work" class="btn">My Work</a>
		</section>

		<section class="about-me" id="about">
			<h2 class="section__title section__title--about">Who I am</h2>
			<p class="section__subtitle section__subtitle--about">Motivated Developer</p>
			
			<div class="about-me__body">
			<p>I code to solve problems and finish projects. Doing projects and by immersing myself in the design process is how I learn best.  When I want to create something, I learn the syntax, APIs or frameworks necessary to complete the project.</p>
			<p></p>	
			</div>
			<img src="full.jpeg" alt="" class="about-me__img">
		</section>

		<section class="my-work" id="work">
			<h2 class="section__title section__title--work">My Work</h2>
			<p class="section__subtitle section__subtitle--work">Some projects I've completed</p>

			<div class="portfolio">
				<a href="portfolio project.html" class="portfolio__item">
					<img src="ses (6).JPG" alt="" class="portfolio__img">
				</a>

				<a href="#" class="portfolio__item">
					<img src="" alt="" class="portfolio__img">
				</a>
				
				<a href="#" class="portfolio__item">
					<img src="" alt="" class="portfolio__img">
				</a>

				<a href="#" class="portfolio__item">
					<img src="" alt="" class="portfolio__img">
				</a>

				<a href="#" class="portfolio__item">
					<img src="" alt="" class="portfolio__img">
				</a>

				<a href="#" class="portfolio__item">
					<img src="" alt="" class="portfolio__img">
				</a>
			</div>
		</section>

		<footer class="footer">
			<a href="mailto:ervin.john.gonzales@gmail.com" class="footer__link">ervin.john.gonzales@gmail.com</a>
			
			<ul class="social-list">
				<li class="social-list__item">
					<a class="siocial-list__link" href="https://www.linkedin.com/in/ervin-john-gonzales-458007157/"><i class="fab fa-linkedin"></i></a>
				</li>
				<li class="social-list__item">
					<a class="siocial-list__link" href="https://github.com/ErvinJohnGonzales"><i class="fab fa-github-square"></i></a>
				</li>
			</ul>
			<a class="footer__link">0449658516</a>
		</footer>

		<script src="index.js"></script>

	</body>
		
</html>