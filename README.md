<html lang="en">
<!-- divinectorweb.com -->
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Resume website html css</title>
  <style>
      * {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
	font-family: 'Montserrat', sans-serif;
}
body {
	background: #00b6c4;
}
.container {
	background: #f5f5f5;
	max-width: 800px;
	margin: 60px auto;
	height: 1250px;
	padding: 20px;
	box-shadow: 0 2px 20px rgba(0, 0, 0, 0.3);
}
.header {
	text-align: center;
}
.header h1 {
	margin-bottom: 10px;
}
.header h3 {
	text-transform: uppercase;
	font-size: 15px;
	font-weight: 500;
}
.img-area {
	width: 200px;
	height: 200px;
	border-radius: 50%;
	overflow: hidden;
	margin: 25px auto;
	border: 15px groove deepskyblue;
}
.img-area img {
	width: 100%;
}
.main {
	display: flex;
	flex-wrap: wrap;
}
.left {
	flex: 1;
	padding: 30px;
}
.left p {
	line-height: 2;
}
.left ul li {
	line-height: 2;
}
h2 {
	background: #00b6c4;
	padding: 15px;
	color: #fff;
	margin: 30px 0;
	font-size: 20px;
	border-radius: 0 50px 50px 0;
}
.right {
	flex: 1;
	padding: 30px;
}
.right h3 {
	margin-bottom: 15px;
}
.right p {
	line-height: 2.9;
}
.right ul li {
	line-height: 2;
}
@media only screen and (min-width: 768px) and (max-width: 991px) {
	.container {
		width: 95%;
		height: auto;
	}
	h2 {
		font-size: 18px;
	}
}
@media screen and (max-width: 600px) {
	.main {
		flex-direction: column;
	}
	.left, .right {
		flex: none;
		width: 100%;
	}
	.container {
		width: 95%;
		height: auto;
	}
	h2 {
		font-size: 15px;
	}
}
  </style>
    </head>
<body>    
    <div class="container">
      <div class="header">
        <div class="img-area">
            <img src="E:\Deep\deep\pics.jpg"alt="">
        </div>
        <h1>Deep Mendapara</h1>
        <h3>Full-Stack Web Developer</h3>
      </div>

      <div class="main">
        <div class="left">
          <h2>Personal Information</h2>
          <p><strong>Name:</strong> Deep Mendapara</p>
          <p><strong>Age:</strong> 21</p>
          <p><strong>Email:</strong> deepmendapara123@gmail.com</p>
          <p><strong>Phone:</strong> 7575895459</p>
          <h2>Skills</h2>
          <ul>
            <li>HTML/CSS</li>
            <li>JavaScript</li>
			<li>Node.js</li>
			<li>React</li>
            <li>SQL</li>
          </ul>
          <h2>Education</h2>
          <h3>Bachlor Of Computer Application</h3>
          <p>University of VNSGU, 2022-2024</p> <br>
        </div>
        
        <div class="right">
          <h2>Work Experience</h2>
          <h3>ABC Company</h3>
          <p><strong>Position:</strong> Software Developer</p>
          <p><strong>Duration:</strong> 2023-2024</p>
          <ul>
            <li>Developed and maintained web applications using React, Node.js, and SQL</li>
            <li>Implemented responsive design using CSS flexbox and media queries</li>
            <li>Collaborated with cross-functional teams to deliver high-quality software products</li>
          </ul> <br>
          <h3>ABC Company</h3>
          <p><strong>Position:</strong> Web Developer</p>
          <p><strong>Duration:</strong> 2023</p>
          <ul>
            <li>Created and maintained websites using HTML, CSS, and JavaScript</li>
            <li>Optimized website performance and user experience using best practices</li>
            <li>Worked with clients to understand their needs and deliver custom solutions</li>
          </ul>
        </div>
      </div>
    </div> 

</body>
</html>


