# Ex.07 Software Product Company Website
## Date:01/05/2024

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
        <title> SOFTWARE DEVELOPMENT COMPANY </title>
       
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(88, 185, 255, 0.75)),url(background.jpg);
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
                color: #ff0000;
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
                color: rgb(0, 247, 255);
            } 
            ::placeholder {
                color: rgb(0, 200, 255);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #00d0ff;
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
                color: rgb(255, 255, 255);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #0091ff;
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
                color: rgb(0, 221, 255);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: rgb(255, 255, 255);
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid #00f7ff;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(0, 140, 255);
                border-radius: 30px;
                background-color: #00f7ff;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #ffffff;
                color: #009dff;
                background-color: rgb(255, 255, 255);
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid #00ffff;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(0, 140, 255);
                border-radius: 30px;
                background-color: #00ffff;
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
                background-color: #ffffff;
                margin-top: auto;
            }
        </style>
    </head>
    <body style= "background-image: url('soft.jpg')" align="center">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">WEB<span>DEVELOPMENT</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
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
                <h2> SOFTWARE DEVELOPMENT COMPANY </h2>
                <br>
                <p> Welcome brings marketing teams together in a single workspace to share plans.  We are 100+ professional software engineers with more than 10 years experience in delivering superior products </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <p>Copyright@2024 Developed by NITHISH KUMAR S (212223240109)</p>
    </footer>
   
</body>
</html>
```
```
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
        background-image: linear-gradient(rgba(0, 0, 0, 0.75),rgba(190, 105, 255, 0.75)),url(background.jpg);
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
        color: rgb(43, 0, 255);
        background-color: #ee00ff;
        border-radius: 30px;
    }
    .logo {
        color: #ff0000;
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
        color: white;
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
    .phases {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: #6fa1f8;
        transition: 0.5s; 
        cursor: pointer;
        border-radius: 30px;
        
    }
    <br></br>
    <br></br>
    
    .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
        <br></br>
    }
    .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 20px;
        <br></br>
    }
    <br></br>
    .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0,0,0,.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
    }
    <br></br>
    .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
    }
    .container .box-container .box h2 {
        color: #6fa1f8;
        font-size: large;
        padding: 10px 0;
    }
    .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
    }
    footer {
        background-color: #c96ef7;
        margin-top: auto;
    }
    .product {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: #e600ff;
        transition: 0.5s; 
        cursor: pointer;
        border-radius: 30px;
        
    }
    .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0,0,0,.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
    }
    .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
    }
    .container .box-container .box h2 {
        color: #6fa1f8;
        font-size: large;
        padding: 10px 0;
    }
    .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
    }
</style>
</head>
<body style= "background-image: url('softw.png')" align="center">
   
<div class="banner">
<br>
<div class="navbar">
    <h1 class="logo">WEB<span>DEVELOPMENT</span></h1>
    
    <ul>
        <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
        <li><a href="http://127.0.0.1:8000/static/product.html" class="bg-product"> Products </a></li>
        <li><a href="http://127.0.0.1:8000/static/person.html"> person </a></li>
        <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
    </ul>
    <form action="" method="get">
        <input type="text" placeholder="Enter to Search">
        <button type="submit"> Search </button>
    </form>
</div>
<div class="phases">
    <h2>SIX PHASES OF THE SOFTWARE DEVELOPMENT LIFECYCLE</h2>

</div>

<div class="container">
   
    <div class="box-container">
        <div class="box">
            
            <h2>ANALYSIS</h2>
            <p> Product Owner</p>
            <p> Project Manager</p>
            <p> Business Analyst</p>
            <p> CTO</p>
        </div>
        <div class="box">
           
            <h2> DESIGN</h2>
            <p> System Architect</p>
            <p> UX/UI designer</p>
            
        </div>
        <div class="box">
            
            <h2>DEVELOPMENT</h2>
            <p> Front-end Developer</p>
            <p> Back-end Developer</p>
        </div>
        <div class="box">
            
            <h2> TESTING </h2>
            <p> Solutions Architect </p>
            <p> QA Engineer</p>
            <p> Tester</p>
            <p> DevOps</p>
        </div>
        <div class="box">
           
            <h2> DEPLOYMENT </h2>
            <p> Data Administrator </p>
            <p> DevOps</p>
        </div>
        <div class="box">
            
            <h2> MAINTENANCE </h2>
            <p>Users</p>
            <p>Testers</p>
            <p>Support Managers</p>

        </div>
       
    </div>
    <div class="product">
        <h2>SOFTWARE PRODUCT DEVELOPMENT</h2>
    
    </div>
    <div class="box-container">
        <div class="box">
            
            <h2> CodeForge Pro</h2>
            <p> Streamlined collaborative coding platform. </p>
            
        </div>
        <div class="box">
           
            <h2> SiteGenie Builder</h2>
            <p> Simplified drag and drop website creation. </p>
            
        </div>
        <div class="box">
            
            <h2>WebOptiMate Suite </h2>
            <p> Enhanced web performance optimization. </p>
        </div>
        <div class="box">
            
            <h2>  CodeLeap Toolkit </h2>
            <p> Tools for innovative web development. </p>
        </div>
        <div class="box">
           
            <h2> WebScale Pro Manager </h2>
            <p> Seamless high-traffic handling. </p>
        </div>
        <div class="box">
            
            <h2> DevInspect Test Kit </h2>
            <p> Automated testing and debugging. </p>

        </div>
       
    </div>
</div>
</div>


<footer>
    <p>Copyright@2024 Developed by NITHISH KUMAR S (212223240109)</p>
</footer>
</body>
</html>


```
```

person.html

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
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(242, 0, 255, 0.75)),url(background.jpg);
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
                background-color: #e100ff;
                border-radius: 30px;
            }
            .logo {
                color: #ff0000;
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
                background: #c16ff8;
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
                color: white;
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
                background-color: #ff25ba;
                margin-top: auto;
            }
        </style>
    </head>
<body style= "background-image: url('sof.jpeg')" align="center">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">WEB<span>DEVELOPMENT</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/person.html" class="bg-people"> People </a></li>
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
                    <td> <img src="cover.jpg"></td>
                    <td> <img src="avinash st.jpg"></td>
                    <td> <img src="HARI.jpg"> </td>
                    <td> <img src="sakthi.jpg"> </td>
                    <td> <img src="pradeep.jpg"> </td>
                    <td> <img src="gokkul.png"> </td>
                </tr>
                <tr align="center">
                    <th> NITHISH</th>
                    <th> AVINASH</th>
                    <th> HARIHARAN</th>
                    <th>SAKTHI</th>
                    <th>PRADEEP</th>
                    <th>GOKKUL</th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                    <td>Dy.Director</td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <p>Copyright@2024 Developed by NITHISH KUMAR S (212223240109)</p>
    </footer>
</body>
</html>
```

```
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
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0, 187, 255, 0.75)),url(background.jpg);
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
                background-color: #00e1ff;
                border-radius: 30px;
            }
            .logo {
                color: rgb(255, 0, 0);
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
                color: white;
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
                background: #00b7ff;
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
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #00e5ff;
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
                border: 3px solid #00f2ff;
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
                color: #6fa1f8;
                font-size: 20px;
            }
            footer {
                background-color: #00bfff;
                margin-top: auto;
            }
        </style>
    </head>
<body style= "background-image: url('so.png')" align="center">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">WEB<span>DEVELOPMAENT</span></h1>
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
                <h2 Contact Information align="center"> </h2>
                <p> <span>Address</span> : No.9 Sannadhi street, Near Perumal Temple, Above Carana Bank, Poonamallee, Chennai -56.</p>
                <p> <span>Email</span> : ajith46@gmail.com </p>
                <p> <span>Phone</span> : +91 9876543210</p>
            </div>
        </div>
    </div>
    <footer>
        <p>Copyright@2024 Developed by NITHISH KUMAR S (212223240109)</p>
    </footer>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (57).png>)
![alt text](<Screenshot (58).png>)
![alt text](<Screenshot (59).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
