# Ex.07 Software Product Company Website
## Date:29-04-24

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> ANIWORLD.CO </title>
        <link rel="icon" href="w.png">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="bootstrap.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
    rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
    crossorigin="anonymous">

        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(bac.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:blueviolet;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color:blueviolet;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:red;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: white;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><img src="we (2).png" alt="" style="height: 100px;">A<span>ni</span>W<span>orld!!</span></h1>
            <ul>
                <li><a href="#"> Home </a></li>
                <li><a href="#"> Subscribtion </a></li>
                
                <li><a href="#"> Genre </a></li>
                <li><a href="#"> LOG IN/ SIGN IN </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Search Anime">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <div>
                    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
                        <div class="carousel-inner" style="height: 500px;position: relative;bottom: 5px;top: 50px;width: 1000px;">
                          <div class="carousel-item active">
                            <img src="mha.jpg" class="d-block w-100" alt="...">
                          </div>
                          <div class="carousel-item">
                            <img src="naruto.jpg" class="d-block w-100" alt="...">
                          </div>
                          <div class="carousel-item">
                            <img src="croe.jpg" class="d-block w-100" alt="...">
                          </div>
                          <div class="carousel-item">
                            <img src="dBZ.jpeg" class="d-block w-100" alt="...">
                          </div>
                          <div class="carousel-item active">
                            <img src="onepiece.jpeg" class="d-block w-100" alt="...">
                          </div>
                        </div>
                      </div>
                </div>
                
            </div>
        </div>  
    </div>
    <footer>
        <center>By RANJAN K (212222230116) </center>
    </footer>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
    crossorigin="anonymous"></script>
</body>
</html>
```


```

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> AniWorld.co </title>
        <link rel="icon" href="w.png">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="bootstrap.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
    rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
    crossorigin="anonymous">
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100%;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(bac.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-people {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: blueviolet;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color:blueviolet;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid white;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: #6fa1f8;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><img src="we (2).png" alt="" style="height: 100px;">A<span>ni</span>W<span>orld!!</span></h1>
            <ul>
                <li><a href="#"> Home </a></li>
                <li><a href="#"> Subscribtion </a></li>
                
                <li><a href="#" class="bg-people"> Genre </a></li>
                <li><a href="#">LOG IN/SIGN IN</a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Search Anime">
                <button type="submit"> Search </button>
            </form>
            <div class="card" style="width: 18rem;height:50px;color: azure;">
                <img src="crd.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h3 class="card-title" style="color: blueviolet;">ONE PIECE</h3>
                  <p class="card-text">A boy who wants to become king of pirates. In his journey how he is gain friends and solve mysteries in his road to become king of pirates.</p>
                  <p>STATUS: ONGOING</p>
                  <P>EPISODES: 1103/?</P>
                  <P>GENRE: Fantasy,Adventure,Mystery</P>
                  <a href="#" class="btn btn-primary">Watch</a>
                </div>
              </div>
              <div class="card" style="width: 18rem;height:50px;color: azure;">
                <img src="aot.webp" class="card-img-top" alt="...">
                <div class="card-body">
                  <h4 class="card-title" style="color: blueviolet;">ATTACK ON TITAN 1</h4>
                  <p class="card-text">Centuries ago humans was started to attack by a monster caled Titans. That Continue's over centuries, now In this era the protoganist was affected by the titans, so he wants to kill all titans.</p>
                  <p>STATUS: Finished</p>
                  <P>EPISODES: 25/25</P>
                  <P>GENRE: Fantasy,Adventure,Mystery,Thriller</P>
                  <a href="#" class="btn btn-primary">Watch</a>
                </div>
              </div>
              <div class="card" style="width: 18rem;height:50px;color: azure;">
                <img src="wb.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h3 class="card-title" style="color: blueviolet;">Wind Breaker</h3>
                  <p class="card-text">sakura Haruka a high school student who have the desire to fight with only strong people. He enters into a school of deliquent to fight with strong people but it was turned out to be a area guarding school .</p>
                  <p>STATUS: ONGOING</p>
                  <P>EPISODES: 5/?</P>
                  <P>GENRE: Fantasy,Adventure,Mystery</P>
                  <a href="#" class="btn btn-primary">Watch</a>
                </div>
              </div>
              <div class="card" style="width: 18rem;height:50px;color: azure;">
                <img src="TIE.webp" class="card-img-top" alt="...">
                <div class="card-body">
                  <h4 class="card-title" style="color: blueviolet;">That Time I Got Reincarnated as a Slime 1</h4>
                  <p class="card-text">an Adult Reincarnated as slime in Isekai and wants to live life peacefully but he couldn't. So how was his life change is the story of this anime.</p>
                  <p>STATUS: ONGOING</p>
                  <P>EPISODES: 4/?</P>
                  <P>GENRE: Fantasy,Adventure</P>
                  <a href="#" class="btn btn-primary">Watch</a>
                </div>
              </div>
        </div>
        <div>BY RANJAN K(212222230116)</div>
        
      
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
    crossorigin="anonymous"></script>
</body>
</html>

```


```

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AniWorld.co</title>
        <link rel="icon" href="w.png">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="bootstrap.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
    rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
    crossorigin="anonymous">
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(bac.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-contact {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color:blueviolet;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            .navbar form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            .navbar form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: red;
            } 
            ::placeholder {
                color: white;
            }
            .navbar form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color:blueviolet;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid #6fa1f8;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: white;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: #6fa1f8;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: white;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color:blueviolet;
                font-size: 20px;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">A<span>ni</span>W<span>orld!!</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/subscribe.html"> Subscribtion </a></li>
                <li><a href="http://127.0.0.1:8000/static/genre.html"> Genre </a></li>
                <li><a href="http://127.0.0.1:8000/static/login.html" class="bg-contact"> LOG IN/ SIGN IN </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Search Anime">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> LOG IN </h1>
                        <center>
                        <input type="text" placeholder="User ID">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <input type="password" placeholder="password">
                        
                        
                        </center>
                        <button type="submit"> Log In </button>
                        <a href="#"><button>Sign In</button></a>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> For Help!! </h2>
                <p> <span>Contact</span> : aniworldco7@gmail.com</p>
                <p> <span>Phone</span> : 044-625-7438</p>
                
            </div>
        </div>
    </div>
   
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
    crossorigin="anonymous"></script>
</body>
</html>
```



## OUTPUT:

![Screenshot 2024-05-06 134727](https://github.com/Ranjanranjan/softweb/assets/130027697/a237ba38-cfdb-4692-80ac-fba05ce96e71)

![Screenshot 2024-05-06 140048](https://github.com/Ranjanranjan/softweb/assets/130027697/c6a6b126-b3b1-480f-96b6-2cef5a06b94c)

![Screenshot 2024-05-06 143559](https://github.com/Ranjanranjan/softweb/assets/130027697/afbc22c3-aa18-46c8-a6ca-28871e664e08)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
