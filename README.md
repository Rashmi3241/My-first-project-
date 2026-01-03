# My-first-project-
Making a website using html and CSS 
<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
</head>
<body>

  <nav>
    <a href="#home">Home</a>         
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
    <a href="#info">Information</a>
  </nav>

  <hr>

  <section id="home">
    <h1>HOME PAGE</h1>
    <p>
      <p>Welcome to my webpage hope you like this let's get started</p>
    </p>
  </section>

  <hr style="height:600px">

  <section id="gallery">
    <h1>Gallery</h1>
    <p>These are my portfolio images.</p>
    <img src="umwelt.natur.jpg" height="120" width="200" alt="Image 1">
    
  </section>

  <hr style="height:600px">

  <section id="contact">
    <h1>Contact</h1>
    <p>You can contact me by following details.</p>
    <h3 align="center>Email- rashmi.ghimire227@gmail.com</h3>
  </section>

  <hr style="height:600px">

  <section id="info">
    <h1>Information</h1>
    <p><h4>I am a class 9 computer science student learning html and css.Tuis is the first drmo of my project</h4>.</p>
  </section>
  <hr style="height:300px"
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Scroll to Top Arrow</title>

</head>
<body>

<button id="scrollTopBtn" title="Go to top">&#8679;</button> <!-- Arrow symbol -->

</body>
</html>
hero-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: #fff;
  z-index: 1;
}

.hero-content h1 {
  font-size: 48px;
  margin-bottom: 15px;
}

.hero-content p {
  font-size: 22px;
  margin-bottom: 25px;
}

.hero-content .bottom {
  padding: 15px 30px;
  font-size: 18px;
  background-color: #ff4d4d;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

.hero-content .bottom:hover {
  background-color: #ff3333;
}
