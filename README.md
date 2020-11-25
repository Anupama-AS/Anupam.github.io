<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>My first Website</title>
        <link rel="stylesheet" type="text/css" href="FirstWebsite.css"/>
        <link rel="shortcut icon" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStSw7GdEFIv_uTxuU1G0-dAobzfWUuox6FmQ&usqp=CAU"/>
	    <style>
		    body{
    margin: 0%;
    padding: 1px;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
*{
	box-sizing:border-box;
	scroll-behavior: smooth;
}
a{
    text-decoration: none;
}
#section{
    width: 100%;
    height:100vh;
    position: relative;
}
nav{
    background-color: #FFFFFF;
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: fixed;
	left: 0;
    top: 0;
    box-shadow: 5px 10px 30px rgba(0,0,0,0.02);
    z-index: 1;
}
ul{
    list-style: none;
    display: flex;
    text-align: center;
}
nav ul li a { 
    height:40px;
	line-height: 43px;
	margin: 4px;
	padding: 0px 22px;
	display: flex;
	font-size: 20;
	text-transform: uppercase;
	font-weight: 500;
	color:#425252;
    letter-spacing: 1px;
    text-align:center;
}
.logo img{
    height:45px;
}
.namaste{
    color:lightseagreen;
	font-weight: 500;
	font-size: 15px;
	border-bottom: 2px solid lightseagreen;
}
nav ul li a:hover{
	background-color:lightsalmon;
	color:#FFFFFF;
	box-shadow: 5px 10px 30px rgba(64,198,196,0.3);
	transition: all ease 0.2s;
}
.model img{
	width:100%;
	height: 100%;
	object-fit: contain;
}
.content{
    width:90%;
	display: flex;
	justify-content: space-around;
	align-items: center;
	position: absolute;
	left: 50%;
	top: 50%;
	transform: translate(-50%,-50%);
}
.model{	width:500px;
	height: 500px;
}

.main-text{
    width:500px;
}
.main-text h1{
	font-size: 40px;
	color:#060607;
	margin:0px 0px 10px 0px;
	line-height: 60px;
}
.main-text p{
	color:#0f0e0e;
}
.portfolio-btn{
    background-color: #420bc4;
    text-decoration-color: black;
	transition: all ease 0.2s;
}
.portfolio-btn{
	width:190px;
	height: 44px;
	display: flex;
	justify-content: center;
	align-items: center;
	color:#FFFFFF;
	background-color: lightcoral;
	border-radius: 20px;
	box-shadow: 4px 10px 30px rgba(24,139,119,0.2);
}
#skills{
	display: flex;
	justify-content: space-around;
	align-items: center;
	width:90%;
    margin:auto auto 50px auto;
    display: flex;
}
.skill-text{
	width:400px;
}
.skill-heading span{
	color:#0c8684;
	font-weight: 500;
	text-transform: uppercase;
	letter-spacing: 1px;
	font-size: 20px;
}
.skill-heading h2{
	color: #0e1011;
	font-size: 3.3rem;
	margin:0px;
	font-weight: 400;
	letter-spacing: 1px;
}
.s-box-text strong{
	color:blueviolet;
	margin: 0px;
	font-size: 20px;
	font-weight: 600;
}
.s-box-text p{
	color:black;
	font-size: 15px;
}
#contact{
	display:flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	margin:40px 0px;
}
.contact-input{
	width:400px;
	height:50px;
	background-color:#FFFFFF;
	display:flex;
	justify-content: center;
	border-radius: 50px;
	box-shadow: 2px 2px 30px rgba(0,0,0,0.15);
}
.contact-input input{
	width:100%;
	background-color: transparent;
	border:none;
	outline: none;
	text-align: center;
	color:#242425;
}
.contact-input a{
	width:200px;
	height:35px;
	background-color:lightcoral;
	color:#FFFFFF;
	display: flex;
	font-size: 0.9rem;
	justify-content: center;
	align-items: center;
	margin: auto 10px;
	border-radius: 20px;
	font-weight: 500;
}
footer{
	display:flex;
	justify-content: space-around;
	border-top: 1px solid rgba(232,232,232,0.5);
	background-color:#FFFFFF;
}
footer p{
	margin:15px 0px;
	color:#5f5f5f;
	font-size: 0.9rem;
}
nav .menu-btn,
.menu-icon{
		display:none;
	}
	    </style>    
    </head>
    <body>
        <section id="section">
            <nav id="nav">
                <a href="#"  class="logo">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStSw7GdEFIv_uTxuU1G0-dAobzfWUuox6FmQ&usqp=CAU"/>
                </a>
                <ul class="menu">
                    <li><a href="#Home">Home</a></li>	
                    <li><a href="#skills">Skills</a></li>			
                    <li><a href="#contact">Contact</a></li>	
                </ul>
                <a href="#" class="namaste">Say namaste!</a>
            </nav>
        </section>
        <div class="content">
            <div class="model">
                <img src="https://thumbs.dreamstime.com/b/smiling-girl-sitting-laptop-learning-coding-cute-web-design-vector-illustration-isolated-white-background-bunner-136584573.jpg"/>	
            </div>
            <div class="main-text">
                <h1>Namaste!I am Anupama</h1>
                <p>This My First Website.</p>
                <a href="#" class="portfolio-btn">See My Portfolio</a>
            </div>
        </div>
        <section id="skills">
            <div class="skill-text">
                <div class="skill-heading">
                    <span>My Skills</span><br>
                    <h2>My Experties</h2><br>
                </div>
              
                <div class="s-box-text">
                    <strong>Hyper Text Markup Language(HTML)</strong><br>
                    <p>I have learnt the basics of HTML</p><br>
                </div>
                </div>
               
                <div class="s-box-text">
                    <strong>Cascading Style Sheets(CSS)</strong><br>
                    <p>I have learnt the basics of CSS</p><br>
                </div>
                </div>
               
                <div class="s-box-text">
                    <strong>JavaScript(Js)</strong><br>
                    <p>I have learnt the basics of JavaScript.</p><br>
                </div>
            </div>
        </section>
        <section id="contact">
            <img src="data:image/jpeg;base64,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"/>
            <div class="contact-input">
                <input type="email" placeholder="Example@gmail.com"/>
                <a href="#">Continue</a>
            </div>
        </section>
            <footer>
                <p>Going To Internet, Ltd Consumer Website</p>
                <p>Copyright 2020 - GoingToInternet</p>
            </footer>
    </body>
</html>



