# ROBOTICS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Robots</title>
    <!--swiperCSS-->
    <link rel="stylesheet" href="css/swiper-bundle.min.css">
    <link rel="stylesheet" href="style.css">
    <!---we had linked our css file----->
</head>
<body>
    <div class="full-page">
        <div class="navbar">
            <div>
                <a href='website.html'>Robots</a>
            </div>
            <nav>
                <ul id='MenuItems'>
                    <li><a href="#">HOME</a>
                    <li><a href='aboutus.html'>About Us</a></li>
                    <li><a href='#'>Services</a></li>
                    <li><a href='#'>Contact</a></li>
                    <li><button class='loginbtn' onclick="document.getElementById('login-form').style.display='block'" style="width:auto;" onclick="home()">Login</button></li>
                </ul>
            </nav>
        </div>

        <div id='login-form'class='login-page'>
            <div class="form-box">
                <div class='button-box'>
                    <div id='btn'></div>
                    <button type='button'onclick='login()'class='toggle-btn'>Log In</button>
                    <button type='button'onclick='register()'class='toggle-btn'>Register</button>
                </div>
                <form id='login' class='input-group-login'>
                    <input type='text'class='input-field'placeholder='Email Id' name="email" required >
		    <input type='password'class='input-field'placeholder='Enter Password' name="password" required>
		    <input type='checkbox'class='check-box'><span>Remember Password</span>
		    <button type='submit'class='submit-btn'>Log in</button>
		 </form>
		 <form id='register' class='input-group-register'>
		     <input type='text'class='input-field'placeholder='First Name' required>
		     <input type='text'class='input-field'placeholder='Last Name ' required>
		     <input type='email'class='input-field'placeholder='Email Id' required>
		     <input type='password'class='input-field'placeholder='Enter Password' required>
		     <input type='password'class='input-field'placeholder='Confirm Password'  required>
		     <input type='checkbox'class='check-box'><span>I agree to the terms and conditions</span>
                    <button type='submit'class='submit-btn'>Register</button>
	         </form>
            </div>
        </div>
            <div id="Home-form" class="Home-page">
                <div class="slide-container swiper">
                    <div class="side-content">
                        <div class="card-warapper swiper-wrapper">
                            <div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/aibone.jpg" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Aibone</h2>
                                    <h3 class="year">2018</h3>
                                    <a href="html/aibone.html"><button class="button"> View More</button></a>
                                </div>
                            </div><div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/kamigami.jpg" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Kamigami</h2>
                                    <h3 class="year">2015</h3>
                                    <a href="html/kamigami.html"><button class="button"> View More</button></a>
                                </div>
                            </div><div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/Robugtix.jfif" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Robugtix</h2>
                                    <h3 class="year">2010</h3>
                                    <a href="html/Robugtix.html"><button class="button"> View More</button></a>
                                </div>
                            </div><div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/amr robots.jfif" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Domino's delivery robot </h2>
                                    <h3 class="year">2017</h3>
                                    <a href="html/Delivery.html"><button class="button"> View More</button></a>
                                </div>
                            </div><div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/Asimo.jfif" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Asimo</h2>
                                    <h3 class="year">2000</h3>
                                    <a href="html/Asimo.html"><button class="button"> View More</button></a>
                                </div>
                            </div><div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/Bionicopter.jfif" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Bionicopter</h2>
                                    <h3 class="year">2013</h3>
                                    <a href="html/bionicopter.html"><button class="button"> View More</button></a>
                                </div>
                            </div>
                            <div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/Flying robot.jfif" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Flying robot</h2>
                                    <h3 class="year">2016</h3>
                                    <a href="html/Flying.html"><button class="button"> View More</button></a>
                                </div>
                            </div>
                            <div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/pepper.jfif" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">pepper</h2>
                                    <h3 class="year">2014</h3>
                                    <a href="html/pepper.html"><button class="button"> View More</button></a>
                                </div>
                            </div>
                            <div class="card swiper-slide">
                                <div class="image-content">
                                    <span class="overlay"></span>
                                    <div class="card-image">
                                        <img src="animal/Roomba.jfif" alt="" class="card-img">
                                    </div>
                                </div>
                                <div class="card-content">
                                    <h2 class="name">Roomba</h2>
                                    <h3 class="year">2002</h3>
                                    <a href="html/Roomba.html"><button class="button"> View More</button></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="swiper-button-next swiper-navBtn"></div>
                    <div class="swiper-button-prev swiper-navBtn"></div>
                    <div class="swiper-pagination"></div>
                </div>
            </form>
        </div>

    </div>
    <script>
        var x=document.getElementById('login');
		var y=document.getElementById('register');
		var z=document.getElementById('btn');
        var w=document.getElementById('home');
		function register()
		{
			x.style.left='-400px';
			y.style.left='50px';
			z.style.left='110px';
		}
		function login()
		{
			x.style.left='50px';
			y.style.left='450px';
			z.style.left='0px';
		}
	</script>
	<script>
        var modal = document.getElementById('login-form');
        window.onclick = function(event) 
        {
            if (event.target == modal) 
            {
                modal.style.display = "none";
            }
        }
    </script>
</body>
    <script src="java/swiper-bundle.min.js"></script>
    <script src="java.js"></script>
</html>


*
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.full-page
{
    height: 100%;
	width: 100%;
	background-image: linear-gradient(rgba(0,0,0,0.4),rgba(0,0,0,0.4)),url(https://wallpapercave.com/wp/wp1994189.jpg);
	background-position: center;
	background-size: cover;
	position: absolute;

}
.navbar
{
    display: flex;
    align-items: center;
    padding: 20px;
    padding-left: 50px;
    padding-right: 30px;
    padding-top: 50px;
}
nav
{
    flex: 1;
    text-align: right;
}
nav ul 
{
    display: inline-block;
    list-style: none;
}
nav ul li
{
    display: inline-block;
    margin-right: 70px;
}
nav ul li a
{
    text-decoration: none;
    font-size: 20px;
    color: white;
    font-family: sans-serif;
}
nav ul li button
{
    font-size: 20px;
    color: white;
    outline: none;
    border: none;
    background: transparent;
    cursor: pointer;
    font-family: sans-serif;
}
nav ul li button:hover
{
    color: aqua;
}
nav ul li a:hover
{
    color: aqua;
}
a
{
    text-decoration: none;
    color: palevioletred;
    font-size: 28px;
}
#login-form
{
    display: none;
}
.form-box
{
    width:380px;
	height:480px;
	position:relative;
	margin:2% auto;
	background:rgba(0,0,0,0.3);
	padding:10px;
    overflow: hidden;
}
.button-box
{
	width:220px;
	margin:35px auto;
	position:relative;
	box-shadow: 0 0 20px 9px #ff61241f;
	border-radius: 30px;
}
.toggle-btn
{
	padding:10px 30px;
	cursor:pointer;
	background:transparent;
	border:0;
	outline: none;
	position: relative;
}
#btn
{
	top: 0;
	left:0;
	position: absolute;
	width: 110px;
	height: 100%;
	background: #F3C693;
	border-radius: 30px;
	transition: .5s;
}
.input-group-login
{
	top: 150px;
	position:absolute;
	width:280px;
	transition:.5s;
}
.input-group-register
{
    top: 120px;
	position:absolute;
	width:280px;
	transition:.5s;
}
.input-field
{
	width: 100%;
	padding:10px 0;
	margin:5px 0;
	border-left:0;
	border-top:0;
	border-right:0;
	border-bottom: 1px solid #999;
	outline:none;
	background: transparent;
}
.submit-btn
{
	width: 85%;
	padding: 10px 30px;
	cursor: pointer;
	display: block;
	margin: auto;
	background: #F3C693;
	border: 0;
	outline: none;
	border-radius: 30px;
}
.check-box
{
	margin: 30px 10px 34px 0;
}
span
{
	color:#777;
	font-size:12px;
	bottom:68px;
	position:absolute;
}
#login
{
	left:50px;
}
#login input
{
	color:white;
	font-size:15;
}
#register
{
	left:450px;
}
#register input
{
	color:white;
	font-size: 15;
}



#Home-form{
	min-height: 100vh;
	display: flex;
	align-items: center;
	justify-content: center;
	background-color: #EFEFEF;
	padding: 3px;
}
.slide-container{
	max-width: 1120px;
	width: 100%;
	padding: 40px 0;
}
.side-content{
	margin: 0 40px;
	overflow: hidden;
	border-radius: 25px;
}
.card{
	border-radius:25px;
	background-color: #FFF;
}
.image-content,
.card-content{
	display: flex;
	flex-direction: column;
	align-items: center;
	padding: 10px 14px;
}
.image-content{
	position: relative;
	row-gap: 5px;
	padding: 25px 0;
}
.overlay{
	position:absolute;
	left: 0;
	top:0;
	height: 100%;
	width:100%;
    background-color: #4070f4;
	border-radius: 25px 25px 0 25px;
}
.overlay::before,
.overlay::after{
	content: '';
	position: absolute;
	right: 0;
	bottom: -40px;
	height: 40px;
	width: 40px;
	background-color: #4070f4;
}
.overlay::after{
	border-radius: 0 25px 0 0;
	background-color: #FFF;
}
.card-image{
	position: relative;
	height: 150px;
	width:150px;
	border-radius: 50%;
	background: #fff;
	padding: 3px;
}
.card-image .card-img{
	height: 100%;
	width: 100%;
	object-fit: cover; 
	border-radius: 50%;
	border: 4px solid#4070f4;

}
.name {
	font-size: 25px;
	font-weight: 500;
	color: #333;
	
}
.year {
	font-size: 17px;
	font-weight: 500;
	color: #707070;
	
}
.button{
	border: none;
	font-size:16px;
	color: #FFF;
	padding: 8px 16px;
	background-color: #4070f4;
	border-radius: 6px;
	margin: 14px;
	cursor: pointer;
	transition: all 0.3s ease;
}
.button:hover{
	background: #265df2;
	transition: colour 0.3s ease;
}
.swiper.navBtn{
	color: #6E93F7;
}
.swiper.navBtn :hover{
	color: #4070f4;
}
.swiper.navBtn::before,
.swiper.navBtn::after{
	font-size: 40px;
}
.swiper-button-next{
	right: 0;

}
.swiper-button-prev{
	left: 0;
}
.swiper-pagination-bullet{
	background-color: #6E93F7;
	opacity: 1;

}
.swiper-pagination-bullet-active{
	background-color: #4070f4;
}
@media screen and (max-width:768px) {
	.side-content{
		margin: 0 10px;
	}
	.swiper.navBtn{
		display: none;
	}
	
}

var swiper = new Swiper(".side-content", {
	slidesPerView: 3,
	spaceBetween: 25,
	loop: true,
	centerSlide:'true',
	fade:'true',
	grabcursour:'true',
	pagination: {
	  el: ".swiper-pagination",
	  clickable: true,
	  dynamicBullets:true,
	},
	navigation: {
	  nextEl: ".swiper-button-next",
	  prevEl: ".swiper-button-prev",
	},
	breakpoints:{
		0:{
			slidesPerView:1,
		},
		520:{
			slidesPerView:2,
		},
		950:{
			slidesPerView: 3,
		},
	}
  });
  
  <!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="style.css">
        <title>About us</title>
        <style>
            h3{
                color: black;
            }
            p{
                color: blueviolet;
            }
        </style>
    </head>
    <body>
        <h1>ECE-B 3rd Year<h3>
        <p>20WH1A0477</p>
        <p>20WH1A0479</p>
        <p>20WH1A0489</p>
        <p>20WH1A04B5</p>
    </body>
</html>
	 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Delivery</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Delivery</h1>
    <img src="https://th.bing.com/th/id/OIP.X8NCbrYYVHDmchQfGKxbGwHaE7?pid=ImgDet&rs=1" name="img" aligin="center">
    <p>
        In Japan, you can get sushi delivered by robot. And in Houston, you can get pizza. Fast-food chain Domino’s has partnered with the robotics company Nuro to launch a pilot program that delivers fresh-made pizzas via self-driving AMR robots. All customers have to do is opt in to Nuro’s R2 delivery service, meet the robot outside when it arrives and enter an access pin to unlock the door and get their pizza
    </p>
    <h3 name="k">CREATOR</h3>
    <p>Domino’s</p>
    <h3 name="k">COUNTRY</h3>
    <p>Japan</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Bionicopter</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Bionicopter</h1>
    <img src="https://s3.amazonaws.com/s3.timetoast.com/public/uploads/photos/13611135/bionicopter.jpg" name="img" aligin="center">
    <p>
        Bionicopter is more maneuverable than previous iterations of flying robots. With a wingspan of 27 inches and a body 19 inches long, this dragonfly robot is a great deal larger than the insects which inspired it. But in slow motion, its wings look just like the real thing. Bionicopter can fly forward, backward and stop abruptly in the air. A carbon fiber body covered in blue polyester performance material make Bionicopter a beautiful bug to behold.
    </p>
    <h3 name="k">CREATOR</h3>
    <p>Festo</p>
    <h3 name="k">COUNTRY</h3>
    <p>Japan</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Pepper</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Pepper</h1>
    <img src="https://th.bing.com/th/id/R.6c70dd11980c8cbc5e24fb66376908ee?rik=%2bNcPbKp4ccsk7w&riu=http%3a%2f%2fcontent.assets.pressassociation.io%2f2018%2f10%2f26155552%2f5432128b-60a6-424c-807f-a0b18ec5dce7.jpeg&ehk=zYxYsubJbmT8cPBVRtIN2E%2fZyJlbWujyA06fe66vwwk%3d&risl=&pid=ImgRaw&r=0" name="img" aligin="center">
    <p>
        Pepper is one of the world’s first human-like robots that can recognize faces and emotions. Created by the Japanese company Softbank, the Pepper robots sold out in minutes when they were first released in 2014. They were designed to interact with humans, answering customer questions, recommending products to retail shoppers, helping people fill out bank forms and assisting with hands-on learning in classrooms.
    </p>
    <h3 name="k">CREATOR</h3>
    <p>
        SoftBank Robotics
    </p>
    <h3 name="k">COUNTRY</h3>
    <p>Japan ,France</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Roomba</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Roomba</h1>
    <img src="https://th.bing.com/th/id/OIP.rdhSx3VN49ENrh02qoMQdwHaEd?pid=ImgDet&w=620&h=374&rs=1" name="img" aligin="center">
    <p>
        One of the world’s most famous AMR robots might be sitting in your house right now. Roomba, built by iRobot in 2002, is a robotic vacuum cleaner that navigates your home using sensors. The first of their kind, Roombas are now in more than 40 million homes worldwide.
    </p>
    <h3 name="k">CREATOR</h3>
    <p>iRobot</p>
    <h3 name="k">COUNTRY</h3>
    <p>American</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Aibone</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Aibone</h1>
    <img src="https://th.bing.com/th/id/OIP.1i8P_4mD3XqUrxq0l7oj2AHaE7?pid=ImgDet&rs=1" name="img" aligin="center">
    <p>
        Aibo is a friendly robotic dog whose personality and behavior evolves over time. It can recognize its owner's face, detect smiles and words of praise, and learn new tricks. And of course, it loves to be petted.
    </p>
    <h3 name="k">CREATOR</h3>
    <p>Sony</p>
    <h3 name="k">COUNTRY</h3>
    <p>Japan</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }

    </style>
</head>
<body>
    <h1 ><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Kamigami</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Kamigami</h1>
    <img src="https://m.media-amazon.com/images/S/aplus-media/vc/9cd53d58-8f56-47a1-ad69-d4dcbbd0c472.jpg" name="img" aligin="center">
    <p>
        Kamigami are app-controlled, build-it-yourself robot kits that mimic the way real creatures move in nature. They are fast and fun to drive.
    </p>
    <h3 name="k">CREATOR</h3>
    <p>Dash Robotics</p>
    <h3 name="k">COUNTRY</h3>
    <p>United States</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Robugtix</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Robugtix</h1>
    <img src="https://i1.wp.com/www.techmymoney.com/wp-content/uploads/2013/07/Robugtix-T8.jpg?fit=766%2C541&ssl=1" name="img" aligin="center">
    <p>
        Our first advanced robot was the T8 spider, for which we used 3D printing methods in a time when very few were using it for robotics. To control the robot, we developed an inverse kinematics engine that amused the world and for this achievement, we received a lot of positive reviews and coverage. After seeing how our T8 entertained the public, we decided to make a mass-produced version of it, the T8X, to make it more accessible for people.

Since then, we’ve also been focusing on helping other organizations in their businesses wherever robotics applied. 
    </p>
    <h3 name="k">CREATOR</h3>
    <p>Robugtix</p>
    <h3 name="k">COUNTRY</h3>
    <p>Hong Kong</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Asimo</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Asimo</h1>
    <img src="https://th.bing.com/th/id/OIP.0DgJvloRxNlBiEgMtJJHqQHaEK?pid=ImgDet&rs=1" name="img" aligin="center">
    <p>
        Honda has spent more than a decade building ASIMO, a humanoid robot that the company hopes will someday help us around the house. ASIMO, which stands for Advanced Step in Innovative Mobility, can communicate in American and Japanese sign language, run at speeds of up to 5.6 miles per hour and predict and respond to its surroundings. Though ASIMO is not currently for sale, Honda hopes it will hit stores by 2030.
    <h3 name="k">CREATOR</h3>
    <p>Honda</p>
    <h3 name="k">COUNTRY</h3>
    <p>Japan</p>
</body>
</html>
	    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Flying Robot</title>
    <style>
        body{
            background: paleturquoise;
            font-size: 20px;
        }
        h1{
            align-items: center;
            color: red;
        }
        k{
            color: rgb(218, 215, 250);
        }
        img{
            width: 500px;
            height: 500px;
        }

    </style>
</head>
<body>
    <h1 >Flying Robot</h1>
    <img src="https://i.pinimg.com/originals/ea/4f/8a/ea4f8a45d96f5c43eba78aec554ce9ff.jpg" name="img" aligin="center">
    <p>
        "Our early ideas of making a flying humanoid robot came up around 2016," Daniele Pucci, head of the Artificial and Mechanical Intelligence lab that carried out the study, told TechXplore. "The main purpose was to conceive robots that could operate in disaster-like scenarios, where there are survivors to rescue inside partially destroyed buildings, and these buildings are difficult to reach because of potential floods and fire around them."
    </p>
    <h3 name="k">CREATOR</h3>
    <p>Daniele Pucci</p>
    <h3 name="k">COUNTRY</h3>
    <p>Japan</p>
</body>
</html>
	    
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.body
{
    height: 100%;
	width: 100%;
	background-image: linear-gradient(rgba(0,0,0,0.4),rgba(0,0,0,0.4)),url(images/bg-2.jpg);
	background-position: center;
	background-size: cover;
	position: absolute;

}
.img{
    position: relative;
	row-gap: 5px;
	padding: 25px 0;
}
