# Ex.07 Software Product Company Website
## Date:24.04.2024

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
software.html

<html>
<head>
  <title>SUSI</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 20px;
    }

    nav .container {
      display: flex;
      align-items: center;
    }

    nav img {
      margin-right: 10px;
    }

    nav h1 {
      margin: 0;
    }

    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }

    nav ul li {
      display: inline;
    }

    nav ul li a {
      text-decoration: none;
      color: #fff;
      margin: 0 15px;
    }

    nav ul li a:hover {
      color: #ffd700; 
    }

    section {
      padding: 50px;
    }
    .home{
        padding-left: 30px;
        margin-bottom: 100px;
        padding-top: 60px;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 8px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    .box{
            text-align: center;
            height: 300px;
            width: 400px;margin-left: 100px;
        }
        .edge{
            padding-left: 900px;
            margin-top: 10px;
        
        } .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: rgb(172, 172, 172);
            width: 400px;
            min-height: 200px;
            font-size: 20px;
            background-color:rgb(141, 146, 146);
              }
              p{
                margin-left: -100px;
              }
              h1{
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-weight: bold;
              }
              input{
                width: 200px;
                height: 30px;
              }

  </style>
</head>
    <body bgcolor="red" background="bage.jpg" style="background-size: cover;">
    <header>
        <nav>
          <div class="container">
            <img src="ps2.png" height="50px" width="80px">
            <h1>SUSIDEVELOPED</h1>
          </div>
          <ul>
            <li><a href="software.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Members</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>
    </div class="imagebg">
    <div class="edge">
        <div class="box">
        <h1 class="heading1">LOGIN HERE</h1>
        <br>
        <br>
        <form>
            <table  cellpadding="5px" cellspacing="5px" >
                <tr>
                    <td>
                        Username:
                    </td>
                    <td>
                        <input type="email" name="name" placeholder="Enter a Email">
                    </td>
                </tr>
                <tr>
                    <td>
                        Password:
                    </td>
                    <td>
                        <input type="password" name="pwd" placeholder="Enter a Password">
                    </td>
                </tr>
                <tr>
                    <td colspan="2">
                        <input type="submit" value="LOGIN" style="background-color: black; color:rgb(148, 150, 24);">
                    </td>
                </tr>
            </table>
            
        </form>
        </div>
    </div>

  <div class="home">
    <h1   style="color:rgb(255, 255, 255);"><br>"Automation is no longer just a problem for those working in manufacturing. Physical labor was replaced by robots; mental labor is going to be replaced by AI and software"</h1>


  <footer>
    <p>&copy; created by Susindhar K. M (212223040218)</p>
  </footer>
</body>
</html>

product.html

<html>
<head>
    <title>Products</title>
    <style>
        
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
          color: white;
        }
    
        header {
          background-color: #333;
          color: #fff;
          padding: 10px 0;
        }
    
        nav {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 0 20px;
        }
    
        nav .container {
          display: flex;
          align-items: center;
        }
    
        nav img {
          margin-right: 10px;
        }
    
        nav h1 {
          margin: 0;
        }
    
        nav ul {
          list-style-type: none;
          margin: 0;
          padding: 0;
        }
    
        nav ul li {
          display: inline;
        }
    
        nav ul li a {
          text-decoration: none;
          color: #fff;
          margin: 0 15px;
        }
    
        nav ul li a:hover {
          color: #ffd700; 
        }
    
        section {
          padding: 50px;
        }
    
        footer {
          background-color: #333;
          color: #fff;
          text-align: center;
          padding: 20px 0;
          position: fixed;
          bottom: 0;
          width: 100%;
        }
        .container1 {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0px;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .product {
      text-align: center;
      margin-bottom: 50px;
      flex-basis: calc(25% - 20px); 
      border: 5px solid #ccc; 
      padding: 20px;
      box-sizing: border-box;
    }

    .product img {
      max-width: 100%;
      height: 200px; 
      width: 200px; 
      object-fit: cover; 
      margin-bottom: 10px;
    }

    .product-info {
      margin-top: 20px;
    }

    .product-name {
      font-weight: bold;
      font-size: 18px;
      color: black;
    }

    .product-description {
      font-size: 16px;
      margin-top: 10px;
      color: black;
    }

    .product-price {
      font-size: 16px;
      margin-top: 10px;
      color: rgb(208, 255, 0); 
    }
    .buy {
      background-color: #007bff;
      color: #fff;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
              h1{
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-weight: bold;
              }
      </style>
</head>
<body bgcolor="blue" background="sa.jbg" style="background-size: cover;"> 
    <header>
        <nav>
          <div class="container">
            <img src="ps2.png" height="50px" width="80px">
            <h1>SUSIDEVELOPED</h1>
          </div>
          <ul>
            <li><a href="software.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Members</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>
      <h1 align="center">Products</h1>
      <div class="container1">
        <div class="product">
          <img src="py.jpg" alt="Product 1">
          <div class="product-info">
            <div class="product-name">PYTHON</div>
            <div class="product-description">Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation.</b></div>


          </div>
        </div>
        <div class="product">
          <img src="c.jpg" alt="Product 2">
          <div class="product-info">
            <div class="product-name">C PROGRAMMING</div>
            <div class="product-description">C is a general-purpose computer programming language. It was created in the 1970s by Dennis Ritchie, and remains very widely used and influential.</div>

          </div>
        </div>
    
        <div class="product" bgcolor="white">
          <img src="sql.jpg" alt="Product 3"> 
          <div class="product-info">
            <div class="product-name">SQL</div>
            <div class="product-description">Structured Query Language is a domain-specific language used to manage data, especially in a relational database management system. </div>


          </div>
        </div>
    
        <div class="product">
          <img src="ph.jpg" alt="Product 4">
          <div class="product-info">
            <div class="product-name">ADOBE PHOTOSHOP</div>
            <div class="product-description">Adobe Photoshop is a raster graphics editor developed and published by Adobe for Windows and macOS. It was originally created in 1987 by Thomas and John Knoll</div>
            

          </div>
        </div>
      </div>

      <footer>
        <p>&copy; 2024 SUSI All rights reserved.</p>
      </footer>
</body>
</html>

sales.html

</html>
 contact
<html>
<head>
    <title>Contact</title>
    <style>
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
        }
    
        header {
          background-color: #333;
          color: #fff;
          padding: 10px 0;
        }
    
        nav {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 0 20px;
        }
    
        nav .container {
          display: flex;
          align-items: center;
        }
    
        nav img {
          margin-right: 10px;
        }
    
        nav h1 {
          margin: 0;
        }
    
        nav ul {
          list-style-type: none;
          margin: 0;
          padding: 0;
        }
    
        nav ul li {
          display: inline;
        }
    
        nav ul li a {
          text-decoration: none;
          color: #fff;
          margin: 0 15px;
        }
    
        nav ul li a:hover {
          color: #ffd700; 
        }
    
        section {
          padding: 50px;
        }
    
        footer {
          background-color: #333;
          color: #fff;
          text-align: center;
          padding: 20px 0;
          position: fixed;
          bottom: 0;
          width: 100%;
        }
    
    

.contact-box {
  max-width: 500px;
  margin: 50px auto;
  margin-top: 120px;
  padding: 30px;
  border: 4px solid black;
  border-radius: 10px;
  text-align: center;
}

.contact-info {
  margin-bottom: 20px;
}

.contact-info p {
  margin: 5px 0;
}

.subscribe-form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.subscribe-form h3 {
  margin-bottom: 10px;
  color: #333;
}

.subscribe-form input[type="email"] {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
  border: 2px solid #ccc;
}

.subscribe-form button {
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

</style>

</head>
<body bgcolor="red" background="contact.jpg" style="background-size: cover;">

    <header>
        <nav>
          <div class="container">
            <img src="ps2.png" height="50px" width="80px">
            <h1>SUSIDEVELOPED</h1>
          </div>
          <ul>
            <li><a href="software.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Members</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>

      <div class="contact-box">
        <h2>Contact Us</h2>
        <p>If you have any questions or concerns, feel free to contact us.</p>
        <div class="contact-info">
          <p>Email: <a href="mailto:susientertainment@gmail.com">susientertainment@gmail.com</a></p>
          <p>Toll Free : 1800 578 9080</p>
        </div>
        <form class="subscribe-form">
          <h3>Subscribe</h3>
          <input type="email" name="email" placeholder="Enter your email address">
          <button type="submit">Subscribe</button>
        </form>
    </div>

      <footer>
        <p>&copy; 2024 SUSI. All rights reserved.</p>
      </footer>
</body>
</html>

member.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Members</title>
    <style>
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
          color: white;
        }
    
        header {
          background-color: #333;
          color: #fff;
          padding: 10px 0;
        }
    
        nav {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 0 20px;
        }
    
        nav .container {
          display: flex;
          align-items: center;
        }
    
        nav img {
          margin-right: 10px;
        }
    
        nav h1 {
          margin: 0;
        }
    
        nav ul {
          list-style-type: none;
          margin: 0;
          padding: 0;
        }
    
        nav ul li {
          display: inline;
        }
    
        nav ul li a {
          text-decoration: none;
          color: #fff;
          margin: 0 15px;
        }
    
        nav ul li a:hover {
          color: #ffd700; 
        }
    
        section {
          padding: 10px;
          text-align: center;
        }
    
        footer {
          background-color: #333;
          color: #fff;
          text-align: center;
          padding: 20px 0;
          position: fixed;
          bottom: 0;
          width: 100%;
        }
        .container1 {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .member {
      text-align: center;
      margin-bottom: 50px;
      flex-basis: calc(25% - 20px); 
      border: 3px solid white; 
      padding: 20px;
      box-sizing: border-box;
    }

    .member img {
      max-width: 100%;
      height: 250px;
      width: 200px; 
      margin-bottom: 20px;
    }

    .member-name {
      font-weight: bold;
      font-size: 18px;
    }

    .member-designation {
      font-size: 16px;
      margin-top: 10px;
    }
    .team{
        padding-left: 20px;
    }
              h1{
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-weight: bold;
              }
    
      </style>
</head>
<body bgcolor="red" background="member.jpg" style="background-size: cover;">
    <header>
        <nav>
          <div class="container">
            <img src="ps2.png" height="50px" width="80px">
            <h1>SUSI ENTERTAINMENT</h1>
          </div>
          <ul>
            <li><a href="software.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Members</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>
    
      <div class="team">
        <h1> Our Team</h1 >
            <p>Team member profiles</p>
      </div>
        
      

      <div class="container1">
        <div class="member">
          <img src="susi.jpeg">
          <div class="member-info">
            <div class="member-name">SUSINDHAR K M</div>
            <div class="member-designation">CEO</div>
          </div>
        </div>
    
        <div class="member">
          <img src="kratos.jpg">
          <div class="member-info">
            <div class="member-name">KRATOS </div>
            <div class="member-designation">CO-FOUNDER</div>
          </div>
        </div>
    
        <div class="member">
          <img src="nathan's Drake.jpg" >
          <div class="member-info">
            <div class="member-name">Nathan</div>
            <div class="member-designation">DIRECTOR</div>
          </div>
        </div>
    
        <div class="member">
          <img src="Franklin.jpg">
          <div class="member-info">
            <div class="member-name">Franklin</div>
            <div class="member-designation">HR </div>
          </div>
        </div>
      </div>
</body>
</html>
```

## OUTPUT:
![alt text](<susin/susin/Screenshot 2024-05-09 143125.png>)
![alt text](<susin/susin/Screenshot 2024-05-09 143139.png>)
![alt text](<susin/susin/Screenshot 2024-05-09 143310.png>)
![alt text](<susin/susin/Screenshot 2024-05-09 143320.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
