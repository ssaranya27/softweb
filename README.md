# Ex.07 Software Product Company Website
## Date:
23/04/2024
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
home.html


<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient white((169, 204, 100, 0.75),white(174, 206, 100, 0.75));
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
                color: rgb(225, 226, 234);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(233, 249, 239);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(194, 99, 177, 0.2);
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
                color: rgb(230, 116, 148);
            } 
            ::placeholder {
                color: rgb(233, 125, 188);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(231, 115, 165);
                border-radius: 10px;
                background: black;
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
                color: rgb(217, 105, 154);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: pink;
                background-color: black;
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
                color: black;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: black;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid black;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: pink;
                border-radius: 30px;
                background-color: black;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid white;
                color: black;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid black;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: pink;
                border-radius: 30px;
                background-color: white;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid black;
                color: black;
                background-color: pink;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: black;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TechSociety</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html class = "bg-home"> home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> <b>CodeMasteryHub</b> </h2>
                <br>
                <p> Welcome to CodeMasteryHub,Forward-Thinking And Innovative Solutions To Bring Your Ideas To Life!</p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by saranya S. 212223220101 </center>
    </footer>
</body>
</html>

product.html


<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(234, 238, 227, 0.75),rgba(250, 250, 249, 0.75));
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
            .bg-product {
                border: 1px;
                padding: 10px;
                color: pink;
                background-color: black;
                border-radius: 30px;
            }
            .logo {
                color: black;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: pink;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(204, 152, 174, 0.2);
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
                color: pink;
            } 
            ::placeholder {
                color: pink;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: pink;
                border-radius: 10px;
                background: black;
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
                color: pink;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: pink;
                background-color: black;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 4%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: pink;
                box-shadow: 0 5px 10px rgba(0,0,0,.3);
                border-radius: 20px;
                background: transparent;
                border: 1px solid pink;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color: black;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: pink;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color: black;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TechSociety</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html" class="bg-product"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <h3>CodeChallengePro</h3>
                    <p>A platform offering daily coding challenges, personalized learning paths, and detailed performance analytics to help users improve their coding skills.</p>
                </div>
                <div class="box">
                    <h3>MentorConnect</h3>
                    <p> An online mentoring platform connecting aspiring programmers with experienced mentors for guidance, code reviews, and career advice. </p>
                </div>
                <div class="box">
                    <h3>SkillBoost Academy</h3>
                    <p>A comprehensive online learning platform offering courses, tutorials, and projects on various programming languages, algorithms, and software development concepts.</p>
                </div>
                <div class="box">
                    <h3>CodeLab</h3>
                    <p>A virtual coding environment with integrated tutorials and exercises, providing hands-on learning experiences for programming beginners.</p>
                </div>
                <div class="box">
                    <h3>TechInterviewPrep</h3>
                    <p> : A specialized program offering mock technical interviews, coding assessments, and interview preparation resources to help users ace their software engineering interviews.</p>
                </div>
                <div class="box">
                    <h3>CodeCareerPro </h3>
                    <p>A career development platform offering resume reviews, interview coaching, and job placement assistance tailored specifically for software developers. </p>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by Mohamed Asil S (23013491) </center>
    </footer>
</body>
</html>

people.html

people.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(232, 220, 225, 0.75),rgba(253, 255, 248, 0.75));
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
                color: pink;
                background-color: black;
                border-radius: 30px;
            }
            .logo {
                color: black;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: pink;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(219, 98, 165, 0.2);
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
                color: pink;
            } 
            ::placeholder {
                color: pink;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: pink;
                border-radius: 10px;
                background: black;
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
                color: pink;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: pink;
                background-color: black;
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
                color: pink;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid pink;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: black;
            }
            footer {
                background-color: black;
                margin-top: auto;
            }``
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TechSphere</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="saran.png"> </td>
                    <td> <img src="prabu.png"> </td>
                    <td> <img src="mohan.png"> </td>
                    <td> <img src="abi.png"> </td>
                    <td> <img src="kamal.png"> </td>
                </tr>
                <tr align="center">*
                    <th> Saranya S</th>
                    <th> Prabu S </th>
                    <th> Mohanselvi S</th>
                    <th> Abhishek E</th>
                    <th> Kamal E</th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by Mohamed Asil S (23013491) </center>
    </footer>
</body>
</html>

contact.html


<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Us Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(255, 253, 255, 0.75),rgba(255, 255, 255, 0.75));
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
                color: pink;
                background-color: white;
                border-radius: 30px;
            }
            .logo {
                color: black;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: pink;
            }
            .navbar form {
                width: 300px;
                height: 40px;
                display: flex;
                background: white(255, 255, 255, 0.2);
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
                color: pink;
            } 
            ::placeholder {
                color: pink;
            }
            .navbar form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: pink;
                border-radius: 10px;
                background: black;
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
                color: pink;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: pink;
                background-color: black;
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
                border: 3px solid pink;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid black;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: pink;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid pink;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: pink;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: black;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid pink;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: pink;
                border-radius: 30px;
                background: black;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: pink;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: pink;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: black;
                font-size: 20px;
            }
            footer {
                background-color: black;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TechSphere</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address</span> : 13,Nehru Street,Anna Nagar, Katpadi ,Vellore</p>
                <p> <span>Email</span> : ssaranya27072005@gmail.com </p>
                <p> <span>Phone</span> : 9626133410</p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by Saranya S.(212223220101) </center>
    </footer>
</body>
</html>

```
## OUTPUT:
![alt text](home.png)
![alt text](product.png)
![alt text](people.png)
![alt text](contact.png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
