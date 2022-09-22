

<!DOCTYPE html>
<html lang="en-US">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Rajat Balda - Home</title>
<meta name="description" content="Rajat Balda - Personal Portfolio">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
<link rel="shortcut icon" type="image/x-icon" href="images/favicon.png">
<link rel="stylesheet" href="css/bootstrap.min.css" type="text/css" media="all">
<link rel="stylesheet" href="css/all.min.css" type="text/css" media="all">
<link rel="stylesheet" href="css/simple-line-icons.css" type="text/css" media="all">
<link rel="stylesheet" href="css/slick.css" type="text/css" media="all">
<link rel="stylesheet" href="css/jquery.mCustomScrollbar.min.css" type="text/css" media="all">
<link rel="stylesheet" href="css/style.css" type="text/css" media="all">
<script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
<script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
</head>
<body>
<div id="preloader">
<div class="outer">
<div class="spinner">
<div class="dot1"></div>
<div class="dot2"></div>
</div>
</div>
</div>
<div class="site-wrapper">
<div class="mobile-header py-2 px-3 mt-4">
<button class="menu-icon mr-2">
<span></span>
<span></span>
<span></span>
</button>
<a href="index.html" class="site-title dot ml-2">Rajat Balda</a>
</div>
<header class="left float-left shadow-dark" id="header">
<button type="button" class="close" aria-label="Close">
<span aria-hidden="true">&times;</span>
</button>
<div class="header-inner d-flex align-items-start flex-column">
<a href="index.html"><img src="images/favicon.png" alt="Rajat Balda" /></a>
<a href="index.html" class="site-title dot mt-3">Rajat Balda</a>
<span class="site-slogan">Student</span>
<nav>
<ul class="vertical-menu scrollspy">
<li><a href="#home" class="active"><i class="icon-home"></i>Home</a></li>
<li><a href="#about"><i class="icon-user"></i>About</a></li>
<li><a href="#education"><i class="icon-graduation"></i>Education</a></li>
<li><a href="#experience"><i class="icon-briefcase"></i>Experience</a></li>
<li><a href="#contact"><i class="icon-phone"></i>Contact</a></li>
</ul>
</nav>
<div class="footer mt-auto">
<ul class="social-icons list-inline">
<li class="list-inline-item"><a href="https://facebook.com/rajat.balda"><i class="fab fa-facebook-f"></i></a></li>
<li class="list-inline-item"><a href="https://twitter.com/rajatbalda"><i class="fab fa-twitter"></i></a></li>
<li class="list-inline-item"><a href="https://instagram.com/rajat_balda"><i class="fab fa-instagram"></i></a></li>
<li class="list-inline-item"><a href="https://in.linkedin.com/in/rajatbalda"><i class="fab fa-linkedin"></i></a></li>
<li class="list-inline-item"><a href="https://github.com/rajatbalda"><i class="fab fa-github"></i></a></li>
</ul>
<span class="copyright"></span>
</div>
</div>
</header>
<main class="content float-right">
<section class="hero background parallax shadow-dark d-flex align-items-center" id="home">
<div class="cta mx-auto mt-2">
<h1 class="mt-0 mb-4">I’m Rajat Balda<span class="dot"></span></h1>
<div class="container">
<span class="text first-text">I'm a</span>
<span class="text sec-text">Student</span>
</div>
<script>
        const text = document.querySelector(".sec-text");

        const textLoad = () => {
            setTimeout(() => {
                text.textContent = "Student.";
            }, 0);
            setTimeout(() => {
                text.textContent = "Developer.";
            }, 4000);
            setTimeout(() => {
                text.textContent = "Blogger.";
            }, 8000);
            setTimeout(() => {
                text.textContent = "Freelancer.";
            }, 12000); //1s = 1000 milliseconds
        }

        textLoad();
        setInterval(textLoad, 16000);
    </script>
<br>
<center>
<a href="#about" class="btn btn-border-light btn-lg"><i class="icon-arrow-down-circle"></i>View More</a>
</center>
</div>
<div class="overlay"></div>
</section>
<section id="about" class="shadow-blue white-bg padding">
<h3 class="section-title">About Me</h3>
<div class="spacer" data-height="80"></div>
<div class="row">
<div class="col-md-3">
</div>
<div class="col-md-9">
<h2 class="mt-4 mt-md-0 mb-4">Hello,</h2>
<p class="mb-0">I am an independent and self-motivated graduate student with Mechatronics Engineering, seeking for an opportunity to prove my skills. Capable of working with minimum supervision, and committed to provide my efforts to every project.</p>
<div class="row my-4">
<div class="col-md-6">
<p class="mb-2">Name: <span class="text-dark">Rajat Balda</span></p>
<p class="mb-0">Birthday: <span class="text-dark">16 February, 2001</span></p>
</div>
<div class="col-md-6 mt-2 mt-md-0 mt-sm-2">
<p class="mb-2">Languages known: <span class="text-dark">English, Telugu, Hindi.</span></p>
<p class="mb-2">Location: <span class="text-dark">Hyderabad, India</span></p>
</div>
</div>
<a href="media/resume.pdf" class="btn btn-default mr-3"><i class="icon-cloud-download"></i>Download Resume</a>
</div>
</div>
</section>
<section id="skills" class="shadow-blue white-bg padding">
<h3 class="section-title">My skills</h3>
<div class="row mt-5">
<div class="col-md-6">
<div class="skill-item">
<div class="skill-info clearfix">
<h4 class="float-left mb-3 mt-0">Auto CAD</h4>
<span class="float-right">90%</span>
</div>
<div class="progress">
<div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="90">
</div>
</div>
<div class="spacer" data-height="50"></div>
</div>
</div>
<div class="col-md-6">
<div class="skill-item">
<div class="skill-info clearfix">
<h4 class="float-left mb-3 mt-0">Fusion 360</h4>
<span class="float-right">85%</span>
</div>
<div class="progress">
<div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="85">
</div>
</div>
<div class="spacer" data-height="50"></div>
</div>
</div>
<div class="col-md-6">
<div class="skill-item">
<div class="skill-info clearfix">
<h4 class="float-left mb-3 mt-0">HTML & CSS</h4>
<span class="float-right">95%</span>
</div>
<div class="progress">
<div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="95">
</div>
</div>
<div class="spacer" data-height="50"></div>
</div>
</div>
<div class="col-md-6">
<div class="skill-item">
<div class="skill-info clearfix">
<h4 class="float-left mb-3 mt-0">PHP</h4>
<span class="float-right"> 80%</span>
</div>
<div class="progress">
<div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="80">
</div>
</div>
<div class="spacer" data-height="50"></div>
</div>
</div>
<div class="col-md-6">
<div class="skill-item">
<div class="skill-info clearfix">
<h4 class="float-left mb-3 mt-0">Python</h4>
<span class="float-right"> 70%</span>
</div>
<div class="progress">
<div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="70">
</div>
</div>
<div class="spacer" data-height="50"></div>
</div>
</div>
<div class="col-md-6">
<div class="skill-item">
<div class="skill-info clearfix">
<h4 class="float-left mb-3 mt-0">Wordpress</h4>
<span class="float-right"> 95%</span>
</div>
<div class="progress">
<div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="95">
</div>
</div>
<div class="spacer" data-height="50"></div>
</div>
</div>
</div>
</section>
<section id="education" class="shadow-blue white-bg padding">
<h3 class="section-title">Education</h3>
<div class="spacer" data-height="80"></div>
<div class="timeline">
<div class="entry">
<div class="title">
<span>2019 - 2022</span>
</div>
<div class="body">
<h4 class="mt-0">Bachelor's of Technology</h4>
<p>7.29 CGPA - Bachelor of Technology in Mechanical Engineering (Mechatronics) | Mahatma Gandhi Institute of Technology, Hyderabad</p>
</div>
</div>
<div class="entry">
<div class="title">
<span>2016 - 2019</span>
</div>
<div class="body">
<h4 class="mt-0">Diploma</h4>
<p>84.85% - Diploma in Mechanical Engineering | TKR College of Engineering & Technology, Hyderabad</p>
</div>
</div>
<div class="entry">
<div class="title">
<span>2003 - 2016</span>
</div>
<div class="body">
<h4 class="mt-0">Schooling</h4>
<p>8.7 GPA - Board of Secondary Education (SSC) | St. Gabrial's Educational High School, Hyderabad</p>
</div>
</div>
<span class="timeline-line"></span>
</div>
</section>
<section id="experience" class="shadow-blue white-bg padding">
<h3 class="section-title">Experience</h3>
<div class="spacer" data-height="80"></div>
<div class="timeline">
<div class="entry">
<div class="title">
<span>2021 - 2022</span>
</div>
<div class="body">
<h4 class="mt-0">Internship</h4>
<p>Contributed to different on-site and off-site projects at <b>Edgeforce Solutions Private Limited,</b> which helped me to gain some skills.</p>
</div>
</div>
<div class="entry">
<div class="title">
<span>2018 - 2019</span>
</div>
<div class="body">
<h4 class="mt-0">Trainee</h4>
<p>Worked with CNC Machine programming and operation at <b>National Small Industries Corporation.</b></p>
</div>
</div>
<span class="timeline-line"></span>
</div>
</section>
<section id="facts" class="shadow-dark color-white background parallax padding-50">
<div class="row relative z-1">
<div class="col-md-4 col-sm-6">
<div class="fact-item text-center">
<i class="icon-docs icon-circle"></i>
<h2 class="count">7</h2>
<span>Certifications</span>
</div>
</div>
<div class="col-md-4 col-sm-6">
<div class="fact-item text-center">
<i class="icon-note icon-circle"></i>
<h2 class="count">5</h2>
<span>Projects</span>
</div>
</div>
<div class="col-md-4 col-sm-6">
<div class="fact-item text-center">
<i class="icon-book-open icon-circle"></i>
<h2 class="count">1</h2>
<span>Publications</span>
</div>
</div>
</div>
<div class="overlay"></div>
</section>
<section id="services" class="shadow-blue white-bg padding">
<h3 class="section-title">Services</h3>
<div class="spacer" data-height="80"></div>
<div class="row">
<div class="col-md-4 col-sm-6">
<div class="service-item text-center">
<i class="icon-globe icon-simple"></i>
<h4 class="my-3">Web Development</h4>
</div>
<div class="spacer" data-height="20"></div>
</div>
<div class="col-md-4 col-sm-6">
<div class="service-item text-center">
<i class="icon-game-controller icon-simple"></i>
<h4 class="my-3">Application Development</h4>
</div>
<div class="spacer" data-height="20"></div>
</div>
<div class="col-md-4 col-sm-6">
<div class="service-item text-center">
<i class="icon-pencil icon-simple"></i>
<h4 class="my-3">Designing</h4>
</div>
<div class="spacer" data-height="20"></div>
</div>
<div class="col-md-4 col-sm-6">
<div class="service-item text-center">
<i class="icon-rocket icon-simple"></i>
<h4 class="my-3">SEO</h4>
</div>
<div class="spacer d-md-none d-lg-none" data-height="20"></div>
</div>
<div class="col-md-4 col-sm-6">
<div class="service-item text-center">
<i class="icon-cloud-upload icon-simple"></i>
<h4 class="my-3">Cloud</h4>
</div>
</div>
<div class="col-md-4 col-sm-6">
<div class="service-item text-center">
<i class="icon-link icon-simple"></i>
<h4 class="my-3">Blockchain</h4>
</div>
<div class="spacer d-md-none d-lg-none" data-height="20"></div>
</div>
</div>
</section>
<section id="contact" class="shadow-blue white-bg padding">
<h3 class="section-title">Get in touch</h3>
<div class="spacer" data-height="80"></div>
<div class="row">
<div class="col-md-4 mb-4 mb-md-0">
<div class="contact-info mb-5">
<i class="icon-phone"></i>
<div class="details">
<h5>Phone</h5>
<span>+91 8125273473</span>
</div>
</div>
<div class="contact-info mb-5">
<i class="icon-envelope"></i>
<div class="details">
<h5>Email address</h5>
<span><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="63000c0d1702001723110209021701020f07024d0a0d">[email&#160;protected]</a></span>
</div>
</div>
</div>
</div>
</section>
</main>
</div>
<a href="javascript:" id="return-to-top"><i class="fa fa-chevron-up"></i></a>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script src="js/jquery-1.12.3.min.js"></script>
<script src="js/jquery.easing.min.js"></script>
<script src="js/popper.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/jquery.waypoints.min.js"></script>
<script src="js/jquery.counterup.min.js"></script>
<script src="js/jquery.mCustomScrollbar.concat.min.js"></script>
<script src="js/isotope.pkgd.min.js"></script>
<script src="js/infinite-scroll.min.js"></script>
<script src="js/imagesloaded.pkgd.min.js"></script>
<script src="js/slick.min.js"></script>
<script src="js/contact.js"></script>
<script src="js/validator.js"></script>
<script src="js/custom.js"></script>
<iframe src="https://api.countapi.xyz/hit/rajatbalda.in/" style="border:0px #ffffff none;" name="stats" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="0px" width="0px" allowfullscreen></iframe>
</body>
</html>
