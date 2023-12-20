# Ex.07 Software Product Company Website
## Date:18.12.2023

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
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PRODUCT BASED SOFTWARE COMPANY</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 100vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(background.jpg);
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
        color:violet;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color:grey;
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
        background: goldenrod;
        cursor: pointer;
      }
      #search.hover {
        border: 1px;
        padding: 10px;
         transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background:blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
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
        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background:blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
      }
      .content {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
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
        border: 2px solid blueviolet;
        padding: 13px 35px;
        letter-spacing: 1px;
        color: white;
        border-radius: 30px;
        background-color: blueviolet;
        text-decoration: none;
      }
      .login:hover {
        border: 2px solid blueviolet;
        color: blueviolet;
        background-color: white;
        transition: 0.5s;
        cursor: pointer;
      }
      .signup {
        margin: 0px 10px;
        border: 2px solid blueviolet;
        padding: 13px 35px;
        letter-spacing: 1px;
        color: white;
        border-radius: 30px;
        background-color: BLU;
        text-decoration: none;
      }
      .signup:hover {
        border: 2px solid green;
        color: #00d5ff;
        background-color: white;
        transition: 0.5s;
        cursor: pointer;
      }
      footer {
        border: 1px;
        padding: 10px;
        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">T<span>IME</span>X<span>PERTS</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html"> Products </a></li>
          <li><a href="people.html"> People </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button id="search" type="submit">Search</button>
        </form>
      </div>
      <div class="content">
        <div class="text">
          <h2>
            WE ARE BUILDING SOFTWARE TO HELP
          </h2>
          <br />
          <br />
          <div>
            <a href="#" class="login"> Log In </a>
            <a href="#" class="signup"> Sign Up </a>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and Developed by SOUNDARYA J (23006091)</center>
    </footer>
  </body>
</html>

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>people page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 100vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(background.jpg);
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
        background-color: blueviolet;
        border-radius: 30px;
      }
      .logo {
        color: violet;
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
        background: blueviolet;
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
        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
      }
      .image {
        position: relative;
        border: 0;
        top: 150px;
        background: transparent;
      }
      .image table {
        border: 0;
        color: white;
        position: relative;
        left: 200px;
      }
      .image table img {
        height: 140px;
        width: 140px;
        border: 2px solid white;
        padding: 5px;
        border-radius: 50%;
      }
      .image table td {
        color: blueviolet;
      }
      footer {
        border: 1px;
        padding: 10px;
        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">T<span>IME</span>X<span>PERTS</span></h1>
        <ul>
          <li><a href="pg 1.html"> Home </a></li>
          <li><a href="PG 2.html"> Products </a></li>
          <li><a href="Pg 3.html" class="bg-people"> People </a></li>
          <li><a href="pg 4.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="image">
        <table cellspacing="20">
          <tr align="center">
            <td><img src="23006091.jpg" /></td>
            <td><img src="surya.jpg" /></td>
            <td><img src="vijay.jpeg" /></td>
            <td><img src="dhanush.jpeg" /></td>
            <td><img src="ar.jpeg" /></td>
            </tr>
          <tr align="center">
            <th>SOUNDARYA</th>
            <th>SIDD AHMED</th>
            <th>VIJAY</th>
            <th>DHANUSH</th>
            <th>AR RAHMAN</th>
            </tr>
          <tr align="center">
            <td>CEO</td>
            <td>CEO,Co-Founder</td>
            <td>CTO,Co-Founder</td>
            <td>DIRECTOR</td>
            <td>Asst.Director</td>
          </tr>
        </table>
      </div>
    </div>
    <footer>
      <center>Designed and Developed by SOUNDARYA J (23006091)</center>
    </footer>
  </body>
</html>

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 200vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(background.jpg);
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
        color: white;
        background-color: blueviolet;
        border-radius: 30px;
      }
      .logo {
        color: violet;
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
        background: blueviolet;
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
        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
      }
      .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
      }
      .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 100px;
      }
      .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
      }
      .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
      }
      .container .box-container .box h3 {
        color: blueviolet;
        font-size: large;
        padding: 20px 0;
      }
      .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
      }
      footer {
        border: 1px;
        padding: 10px;
        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">T<span>IME</span>X<span>PERTS</span></h1>
        <ul>
          <li><a href="pg 1.html"> Home </a></li>
          <li><a href="PG 2.html" class="bg-product"> Products </a></li>
          <li><a href="Pg 3.html"> People </a></li>
          <li><a href="pg 4.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="container">
        <div class="box-container">
          <div class="box">
            <img src="C.png" alt="" />
            <h3>C</h3>
            <p>
              C is a general-purpose programming language created by Dennis
              Ritchie at the Bell Laboratories in 1972.
            </p>
          </div>
          <div class="box">
            <img src="c++.png" alt="" />
            <h3>C++</h3>
            <p>
              C++ is a cross-platform language that can be used to create
              high-performance applications.
            </p>
          </div>
          <div class="box">
            <img src="js.png" alt="" />
            <h3>JAVASCRIPT</h3>
            <p>
              JavaScript is a lightweight, cross-platform, single-threaded, and
              interpreted compiled programming language. I
            </p>
          </div>
          <div class="box">
            <img src="php.jpeg" alt="" />
            <h3>PHP</h3>
            <p>
              PHP is a server side scripting language that is embedded in HTML.
            </p>
          </div>
          <div class="box">
            <img src="PYTHON.png" alt="" />
            <h3>PYTHON</h3>
            <p>
              Python is a popular programming language. It was created by Guido
              van Rossum, and released in 1991.
            </p>
          </div>
          <div class="box">
            <img src="sql.png" alt="" />
            <h3>SQL</h3>
            <p>
              SQL is a standard language for accessing and manipulating
              databases.
            </p>
          </div>
          <div class="box">
            <img src="shell.jpg" alt="" />
            <h3>SHELL</h3>
            <p>
              Shell can be accessed by users using a command line interface.
            </p>
          </div>
          <div class="box">
            <img src="c ash.png" alt="" />
            <h3>C#</h3>
            <p>
              C# is used to develop web apps, desktop apps, mobile apps, games
              and much more.
            </p>
          </div>
          <div class="box">
            <img src="typescript.png" alt="" />
            <h3>TYPESCRIPT</h3>
            <p>
              typeScript is a syntactic superset of JavaScript which adds static
              typing.
            </p>
          </div>
          <div class="box">
            <img src="f.png" alt="" />
            <h3>F#</h3>
            <p>
              F# is an Open-source programming language with a lot of features.
            </p>
          </div>
          <div class="box">
            <img src="swift.jpeg" alt="" />
            <h3>SWIFT</h3>
            <p>
              Swift, developed by Apple, is the go-to language for iOS and macOS
              app development.
            </p>
          </div>
          <div class="box">
            <img src="go.png" alt="" />
            <h3>GO</h3>
            <p>
              Go, also known as Golang, has gained attention for its efficiency,
              simplicity, and strong support for concurrent programming
            </p>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and Developed by SOUNDARYA J (23006091)</center>
    </footer>
  </body>
</html>

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 100vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(background.jpg);
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
        background-color: blueviolet;
        border-radius: 30px;
      }
      .logo {
        color:violet;
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
        background: blueviolet;
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
       transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
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
        border: 3px solid red;
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
        left: 20px;
        border: 1px solid white;
        border-radius: 10px;
        width: 300px;
      }
      .box-1 form button {
        border: 0;
        outline: none;
        padding: 10px 20px;
        color: white;
        border-radius: 30px;
        background:blueviolet;
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
        color: blueviolet;
        font-size: 20px;
      }
      footer {
        border: 1px;
        padding: 10px;
        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: blueviolet;
        color: #081b29;
        box-shadow: 0 0 20px blueviolet;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">B<span>LACK</span>R<span>OCK</span></h1>
        <ul>
          <li><a href="pg 1.html"> Home </a></li>
          <li><a href="PG 2.html"> Products </a></li>
          <li><a href="Pg 3.html"> People </a></li>
          <li><a href="pg 4.html" class="bg-contact"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="box">
        <div class="box-1">
          <form>
            <center>
              <h1>Contact Us</h1>
              <input type="text" placeholder="Your Name" />
              <br />
              <input type="email" placeholder="Your Email" />
              <br />
              <textarea rows="4" cols="40" placeholder="Your Message">
              </textarea>
              <br />
              <button type="submit">Submit</button>
            </center>
          </form>
        </div>
        <div class="box-2">
          <h2>Contact</h2>
          <p>
            <span>Address</span> : Saveetha Nagar, Sriperumbadur Taluk, Kanchipuram - Chennai Rd, Chennai, Tamil Nadu 602105
          </p>
          <p><span>Email</span> : TIMEXPERTS.official@gmail.com</p>
          <p><span>Phone</span> : 9876543210</p>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and Developed by SOUNDARYA J (23006091)</center>
    </footer>
  </body>
</html>


## OUTPUT:
![Alt text](<Screenshot 2023-12-20 221732.png>)
![Alt text](<Screenshot 2023-12-20 221916.png>)
![Alt text](<Screenshot 2023-12-20 221930.png>)
![Alt text](<Screenshot 2023-12-20 221804.png>)
![Alt text](<Screenshot 2023-12-20 221817.png>)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
