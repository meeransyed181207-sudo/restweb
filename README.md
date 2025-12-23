# Ex.06 Restaurant Website
## Date:24/12/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
rest.html
<html>
  <head>
    <title>Home page</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="restname">
        <h1><b>HOTEL BLACK DRAGON</b></h1>
      </div>
      <div class="line">SPICYY OF WORLD CLASS!</div>
      <div class="lines">
        <i>"ONCE U TASTE SPICYY FOLLOWS U."</i>
        <p>
         Spicy food is more than just a meal — it's a burst of fiery flavor that wakes up your senses and excites your taste buds. With every bite, the heat builds, bringing a mix of thrill, enjoyment, and sometimes even tears, yet you still crave more. It adds energy, color, and passion to food, turning a simple dish into a bold, zesty experience that many people can’t resist.
        </p>
      </div>
      <div class="image1">
        <img src="IMGE1.PNG" width="600" height="300" />
      </div>
      <div class="image2">
        <img src="IMGE2.PNG" width="600" height="300" />
      </div>
      <footer class="copyrights">&copy; SYED MEERAN A(25008812)</footer>
    </div>
  </body>
</html>
style.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(BACKPIC.PNG);
    background-size: cover;
}

.contents {
    width: 600px;
    height: 30px;
    border: 20px solid aquamarine;
    padding: 20px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.restname {
    color: rgb(66, 54, 161);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    text-align: left;
    position: relative;
    font-size: 350%;
    top: -50px;
}

.line {
    color: sandybrown;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: left;
    position: relative;
    font-size: 275%;
    top: -120px;
    left: 10px;
}

.lines {
    color: greenyellow;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 150%;
    top: -100px;
}

.image1 {
    position: relative;
    top: -90px;
    left: 100px;
    background-size:contain;
}

.image2 {
    position: relative;
    top: -390px;
    left: 800px;
    background-size:contain;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: rgb(129, 131, 209);
    text-align: center;
    top: -330px;
    left: -20px;
    position: relative;
}
menu.html
<html>
  <head>
    <title>MENU PAGE</title>
    <link rel="stylesheet" href="style2.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="menu">
        <h1><b>MENU</b></h1>
      </div>
      <div class="menugrid">
        <div class="menuitem">
          <img src="chettinad-chicken.jpg.webp" width="300" height="150" />
          <h1>Chettinad Chicken</h1>
          <p>Rs. 400</p>
        </div>
        <div class="menuitem">
          <img src="chicken-palli-palayam.jpg.webp" width="300" height="150" />
          <h1>Chicken Palli Palayam</h1>
          <p>Rs. 200</p>
        </div>
        <div class="menuitem">
          <img src="naatu-kozhi-kulambu-672x420.jpg.webp" width="300" height="150" />
          <h1>Naatu Kozhi Kulambu</h1>
          <p>Rs. 300</p>
        </div>
        <div class="menuitem">
          <img src="thalapakatti-style-mutton-biryani.jpg" width="300" height="150" />
          <h1>Thalapakatti Style Mutton Biryani</h1>
          <p>Rs. 450</p>
        </div>
        <div class="menuitem">
          <img src="Chettinad Meen Varuval.webp" width="300" height="150" />
          <h1>Chettinad Meen Varuval</h1>
          <p>Rs. 170</p>
        </div>
        <div class="menuitem">
          <img src="Prawn Kuzhambu.webp" width="300" height="150" />
          <h1>Prawn Kuzhambu</h1>
          <p>Rs. 200</p>
        </div>
        <div class="menuitem">
          <img src="Pollachi Nandu Kulambu.webp" width="300" height="150" />
          <h1>Pollachi Nandu Kulambu</h1>
          <p>Rs. 250</p>
        </div>
        <div class="menuitem">
          <img src="Strawberry Trifle.jpeg" width="300" height="150" />
          <h1>Strawberry Trifle</h1>
          <p>Rs. 200</p>
        </div>
      </div>
      <footer class="copyrights">&copy; SYED MEERAN A(25008812)</footer>
    </div>
  </body>
</html>
style2.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(BACKPIC.PNG);
    background-size: cover;
}
.contents {
    width: 600px;
    height: 30px;
    border: 20px solid rgb(51, 255, 0);
    padding: 20px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}
.menu {
    color: gray;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: beige;
    
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
    
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: rgb(129, 131, 209);
    text-align: center;
    top: -30px;
    left: -20px;
    position: relative;
}
admin.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style3.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="admin">
        <h1><b>MANAGEMENT TEAM</b></h1>
      </div>
      <div class="admingrid">
        <div class="adminlist">
          <img src="SYED CEO.webp" width="130" height="250" />
          <h1>SYED MEERAN</h1>
          <p class="post">CEO</p>
        </div>
        <div class="adminlist">
          <img src="SURIYA.jpg" width="130" height="250" />
          <h1>SURIYA</h1>
          <p class="post">PROMOTION Manager</p>
        </div>
        <div class="adminlist">
          <img src="NAZRIYA.jpg" width="130" height="250" />
          <h1>NAZRIYA</h1>
          <p class="post">HOTEL Manager</p>
        </div>
        <div class="adminlist">
          <img src="ROBERT.jpeg" width="130" height="250" />
          <h1>ROBERT</h1>
          <p class="post">HR Manager</p>
        </div>
        <div class="adminlist">
          <img src="BILLIE ELLISH.webp" width="130" height="250" />
          <h1>BILLIE ELLISH</h1>
          <p class="post">HEAD CHEF</p>
        </div>
        <div class="adminlist">
          <img src="ROHIT.jpeg" width="130" height="250" />
          <h1>ROHIT SHARMA</h1>
          <p class="post">CAPTAIN OF LABOUR</p>
        </div>
      </div>
      <footer class="copyrights">&copy; SYED MEERAN A (25008812)</footer>
    </div>
  </body>
</html>
style3.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(Background.jpg);
    background-size: cover;
}

.contents {
    width: 600px;
    height: 30px;
    border: 20px solid rgb(51, 255, 0);
    padding: 20px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.admin {
    color: green;
    font-family: 'Times New Roman', Times, serif;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminlist{
    background-color: rgba(255, 0, 144, 0.76);
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminlist img {
    
    width: 100%;
    height: 250px;
    object-fit: cover;
    
}

.adminlist h1 {
    font-size: 30 px;
    color: black;
    margin-top: 15px;
}

.adminlist p {
    color: black;
    margin-bottom: 20px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: rgb(129, 131, 209);
    text-align: center;
    top: -30px;
    left: -20px;
    position: relative;
}
contact.html
<html>
  <head>
    <title>CONTACT PAGE</title>
    <link rel="stylesheet" href="style4.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="contact">
        <h1><b>CONTACT</b></h1>
      </div>
      <div class="info">
        <h1>ADDRESS AT:</h1>
        <p>
          HOTEL BLACK DRAGON<br />143, LINGU Street,<br />TABALA Street, CHENNAI
          600081<br />India
        </p>
        <br />
        <h1>Phone:</h1>
        <p>+91 99621 25097</p>
        <br />
        <h1>Email ID:</h1>
        <p>meeransyed181207</p>
      </div>
      <footer class="copyrights">&copy; SYED MEERAN(25008812)</footer>
    </div>
  </body>
</html>
style4.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(BACKPIC.PNG);
    background-size: cover;
}

.contents {
    width: 600px;
    height: 30px;
    border: 20px solid rgb(51, 255, 0);
    padding: 20px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}
.contact {
    color: red;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.info {
    color: white;
    font-family: Times New Roman;
    position: relative;
    top: -70px;
    left: 50;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: rgb(129, 131, 209);
    text-align: center;
    top: -80px;
    left: -20px;
    position: relative;
}
```


## OUTPUT:
![alt text](<Screenshot (30)-1.png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
