# Ex.06 Restaurant Website
## Date:16/12/2025

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
home.html
<html>
<head>
    <title>Restaurant WebPage</title>
    <link href="styles.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="main">
        <h1>Welcome to our Restaurant</h1>
        <h1 class="brand">Secret Story</h1>
        <h2>Experience the secret of Italian cuisine</h2>
        <p>
            Discover the authentic flavors of Italy at our restaurant, where every dish
            tells a story of tradition and passion. From handmade pastas to rich sauces,
            our menu is crafted to bring you a true taste of Italy. Join us for an
            unforgettable dining experience!
        </p>
    </div>
    <div class="images">
        <img src="1.jpg" alt="Image1">
        <img src="2.jpg" alt="Image2">
        <img src="3.jpg" alt="Image3">
        <img src="4.jpg" alt="Image4">
    </div>
</div>
<div class="footer">
    <h4>POPURI SAHITHYA (25004681)</h4>
</div>
</body>
</html>

styles.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    text-decoration: underline;
    font-weight: bold;
    color: hotpink;
    font-size: 16px;
}
.main {
    text-align: center;
    color: white;
    margin-bottom: 40px;
}
.main h1 {
    font-size: 50px;
}
.main .brand {
    font-size: 70px;
    color: red;
    letter-spacing: 4px;
}
.main h2 {
    margin: 15px 0;
    font-weight: normal;
}
.main p {
    width: 70%;
    margin: 20px auto;
    font-size: 18px;
    line-height: 1.6;
}
.images {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-bottom: 40px;
}
.images img {
    width: 220px;
    height: 160px;
    object-fit: cover;
    border: 5px solid white;
    border-radius: 10px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0;
}

menu.html

<html>
<head>
    <title>Menu Page</title>
    <link href="menu.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="menu-container">
        <h1>MENU</h1>
        <div class="menu-items">

            <div class="menu-card">
                <img src="menu1.jpg">
                <h3>Tiramisu</h3>
                <p>Rs. 150</p>
            </div>

            <div class="menu-card">
                <img src="menu2.jpg">
                <h3>Pizza</h3>
                <p>Rs. 130</p>
            </div>

            <div class="menu-card">
                <img src="menu3.jpg">
                <h3>Ravioli</h3>
                <p>Rs. 475</p>
            </div>

            <div class="menu-card">
                <img src="menu4.jpg">
                <h3>Pesto</h3>
                <p>Rs. 170</p>
            </div>

            <div class="menu-card">
                <img src="menu5.jpg">
                <h3>Chicken Parmesan</h3>
                <p>Rs. 650</p>
            </div>

            <div class="menu-card">
                <img src="menu6.jpg">
                <h3>Arancini</h3>
                <p>Rs. 305</p>
            </div>

            <div class="menu-card">
                <img src="menu7.jpg">
                <h3>Tortellini</h3>
                <p>Rs. 450</p>
            </div>

            <div class="menu-card">
                <img src="menu8.jpg">
                <h3>Panna Cotta</h3>
                <p>Rs. 320</p>
            </div>
        </div>
    </div>

</div>
<div class="footer">
    <h4>POPURI SAHITHYA (25004681)</h4>
</div>

</body>
</html>

menu.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Georgia, serif;
}

.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}

.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}

.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}

.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
    font-size: 16px;
}

.menu-container {
    width: 100%;
}

.menu-container h1 {
    font-size: 80px;
    color: yellow;
    letter-spacing: 6px;
    margin-bottom: 35px;
    text-align: center;
    text-decoration: underline;
}

.menu-items {
    display: flex;
    gap: 20px;
    justify-content: center;   
    align-items: flex-start;
    flex-wrap: nowrap;
}

.menu-card {
    background-color: blanchedalmond;
    width: 180px;
    padding: 12px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.35);
}

.menu-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    border-radius: 12px;
    margin-bottom: 10px;
}

.menu-card h3 {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 5px;
}

.menu-card p {
    font-size: 14px;
    color: black;
}
@media (max-width: 1200px) {
    .menu-items {
        flex-wrap: wrap;
        justify-content: center;
    }
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

admin.html

<html>
<head>
    <title>Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <h1 class="admin-title">ADMIN'S</h1>
    <div class="team-container">

        <div class="team-card">
            <img src="admin1.jpeg">
            <h3>Popuri Sahithya</h3>
            <p>CEO</p>
        </div>

        <div class="team-card">
            <img src="admin2.jpg">
            <h3>Hattori</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="team-card">
            <img src="admin3.jpg">
            <h3>Sinzu</h3>
            <p>Operations Manager</p>
        </div>

        <div class="team-card">
            <img src="admin4.jpg">
            <h3>Motu</h3>
            <p>HR Manager</p>
        </div>

        <div class="team-card">
            <img src="admin5.png">
            <h3>Dora</h3>
            <p>Executive Chef</p>
        </div>

        <div class="team-card">
            <img src="admin6.jpg">
            <h3>Shinchan</h3>
            <p>Customer Service Manager</p>
        </div>

        <div class="team-card">
            <img src="admin7.png">
            <h3>Doraemon</h3>
            <p>Managing Director</p>
        </div>

    </div>
</div>
<div class="footer">
    <p>&copy;POPURI SAHITHYA(25004681)</p>
</body>
</html>

admin.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
}
.admin-title {
    font-size: 80px;
    color: greenyellow;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.team-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}
.team-card {
    background-color: blanchedalmond;
    width: 200px;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(0,0,0,0.35);
}
.team-card img {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}
.team-card h3 {
    font-size: 18px;
    margin-bottom: 5px;
}
.team-card p {
    font-size: 14px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

contact.html

<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>

<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="contact-content">
        <h1 class="contact-title">CONTACT</h1>
        <div class="contact-details">
            <h2>Come And Visit us at:</h2>
            <p>
                Secret Story<br>
                7, Z-183, 5th Ave, Z Block<br>
                Anna Nagar, Chennai 600040<br>
                India
            </p>
            <h2>Phone:</h2>
            <p>+91 98419 04638</p>
            <h2>Email ID:</h2>
            <p>secretstoryoffcial@gmail.com</p>
        </div>
    </div>
</div>
<div class="footer">
    <p>&copy;POPURI SAHITHYA(25004681)</p>
</div>
</body>
</html>

contact.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
}
.contact-content {
    color: white;
    margin-top: 40px;
}
.contact-title {
    font-size: 90px;
    color: orange;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.contact-details h2 {
    font-size: 26px;
    margin: 25px 0 10px;
    text-align: center;
}
.contact-details p {
    font-size: 18px;
    line-height: 1.6;
    text-align: center;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

```

## OUTPUT:
![alt text](<WhatsApp Image 2025-12-16 at 11.53.51 PM.jpeg>)

![alt text](<WhatsApp Image 2025-12-16 at 11.58.12 PM.jpeg>)

![alt text](<WhatsApp Image 2025-12-17 at 1.00.02 AM.jpeg>)

![alt text](<WhatsApp Image 2025-12-17 at 1.21.14 AM.jpeg>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
