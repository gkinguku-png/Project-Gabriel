# Project-Gabriel
Project Gabriel for OUK
<!DOCTYPE html>
<html>

<head>
	<title>Gabriel Kinguku</title>


	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1" />

	<link href="https://fonts.googleapis.com/css2?family=Russo+One&display=swap" rel="stylesheet">

	<link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&family=Russo+One&display=swap"
		rel="stylesheet">

	<link rel="stylesheet" type="text/css" href="default.css">
	<link id="theme-style" rel="stylesheet" type="text/css" href="">
</head>

<body>

	<section class="s1">
		<div class="main-container">
			<div class="greeting-wrapper">
				<h1>Hi, I'm Gabriel Kinguku Wanjeru</h1>
			</div>


			<div class="intro-wrapper">
				<div class="nav-wrapper">

					<!-- Link around dots-wrapper added after tutorial video -->
					<a href="index.html">
						<div class="dots-wrapper">
							<div id="dot-1" class="browser-dot"></div>
							<div id="dot-2" class="browser-dot"></div>
							<div id="dot-3" class="browser-dot"></div>
						</div>
					</a>


					<ul id="navigation">
						<li><a href="index.html#contact">Contact</a></li>
						<li><a href="privacy.html">Privacy</a></li>

					</ul>
				</div>

				<div class="left-column">
					<img id="profile_pic" src="images/Gabriel.jpg">
					<h5 style="text-align: center;line-height: 0;">Personalize Theme</h5>

					<div id="theme-options-wrapper">
						<div data-mode="light" id="light-mode" class="theme-dot"></div>
						<div data-mode="blue" id="blue-mode" class="theme-dot"></div>
						<div data-mode="green" id="green-mode" class="theme-dot"></div>
						<div data-mode="purple" id="purple-mode" class="theme-dot"></div>
					</div>

					<p id="settings-note">*Theme settings will be saved for<br>your next visit</p>
				</div>

				<div class="right-column">

					<div id="preview-shadow">
						<div id="preview">
							<div id="corner-tl" class="corner"></div>
							<div id="corner-tr" class="corner"></div>
							<h3>What I Do</h3>
							<p>I create WordPress websites, Static HTML sites, Web Applications, SEO and Mobile Apps
								Development both Android and Ios Platforms</p>
							<div id="corner-br" class="corner"></div>
							<div id="corner-bl" class="corner"></div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section class="s2">
		<div class="main-container">

			<div class="about-wrapper">
				<div class="about-me">
					<h4>More about me</h4>

					<p>Well-qualified Full Stack
						Developer familiar with a wide
						range of programming utilities
						and languages.</p>
					<p>Knowledgeable
						of backend and frontend
						development requirements</p>
					<p>Able to handle any part of the
						process with ease. Collaborative
						team player with excellent
						technical abilities</p>
					<p>While I keep busy coding, I still take interviews in search of a great team & projects
						that interest me.</p>


					<hr>

					<h4>TOP EXPERTISE</h4>

					<p>Fullstack developer with primary focus on React + React Native: <a target="_blank"
							href="resume.pdf">Download Resume</a></p>

					<div id="skills">
						<ul>
							<li>HTML</li>
							<li>CSS</li>
							<li>Vanilla JavaScript</li>
							<li>React / React Native</li>
							<li>WordPress</li>
						</ul>

						<ul>
							<li>Google Maps API</li>
							<li>Redux</li>
							<li>Firebase</li>
							<li>Heroku</li>
							<li>Netlify</li>
						</ul>

					</div>

				</div>


				<div class="social-links">
					<img id="social_img" src="images/LinkedIn.jpg">
					<h3>Find me on Yahoo & LinkedIn</h3>

					<a target="_blank" href="https://www.linkedin.com/in/gabriel-king-uku-084322a2</a>
					<br>
					<a target="_blank" href="https://gmail.com/">gmail: gkinguku@gmail.com</a>
				</div>
			</div>

		</div>
	</section>

	<section class="s1">
		<div class="main-container">
			<h3 style="text-align: center;">Some of my past projects</h3>

			<div class="post-wrapper">

				<div>
					<div class="post">
						<img class="thumbnail" src="images/home.jpg">
						<div class="post-preview">
							<h6 class="post-title">Non Profit Organizations' Website</h6>
							<p class="post-intro">Designed built & mantained the above website for Global Peace
								Initiative</p>
							<a target="_blank" href="https://globalpeaceinitiative.or.ke/">Read More</a>
						</div>
					</div>
				</div>

				<div>
					<div class="post">
						<img class="thumbnail" src="images/memories.jpg">
						<div class="post-preview">
							<h6 class="post-title">Web Application - Memories App</h6>
							<p class="post-intro">A web application where users can post photos and captions of their
								best moments.
							</p>
							<a href="post.html">Read More</a>
						</div>
					</div>
				</div>

				<div>
					<div class="post">
						<img class="thumbnail" src="images/main.jpg">
						<div class="post-preview">
							<h6 class="post-title">Gamezone Rating App</h6>
							<p class="post-intro">Developed a game rating app where different people could rate
								the games they play between 1 - 5</p>
							<a href="gamezone.html">Read More</a>
						</div>
					</div>
				</div>

			</div>
		</div>
	</section>

	<section class="s2">
		<div class="main-container">
			<a href=""></a>
			<h3 style="text-align: center;">Get In Touch</h3>

			<form id="contact-form">
				<a name="contact"></a>

				<label>Name</label>
				<input class="input-field" type="text" name="name">

				<label>Subject</label>
				<input class="input-field" type="text" name="subject">

				<label>Email</label>
				<input class="input-field" type="text" name="email">

				<label>Message</label>
				<textarea class="input-field" name="message"></textarea>

				<input id="submit-btn" type="submit" value="Send">
			</form>
		</div>
	</section>

	<script type="text/javascript" src="script.js"></script>
</body>

</html>
