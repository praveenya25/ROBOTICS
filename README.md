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
