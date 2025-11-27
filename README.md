### NAME: SURYA P <br>
### REG NO: 212224230280 <br> 
### Date: 30/10/2025

## EX. No. 7 : WEBSITE FOR RESTAURANT

## AIM :
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1
Requirement collection.

### Step 2
Creating the layout using HTML and CSS.

### Step 3
Updating the sample content.

### Step 4
Choose the appropriate style and color scheme.

### Step 5
Validate the layout in various browsers.

### Step 6
Validate the HTML code.

### Step 7
Publish the website in the given URL.

## PROGRAM :

### admin.html :
```html
<!DOCTYPE html>
<html>
<head>
    <title>Administration - Good Kitchen</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header><h1>Administration Team</h1></header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="admin-grid">

    <div class="admin-card"><img src="images/admin1.jpg"><h3>John Mathew</h3><p>General Manager</p></div>
    <div class="admin-card"><img src="images/admin2.jpg"><h3>Priya Sharma</h3><p>Head Chef</p></div>
    <div class="admin-card"><img src="images/admin3.jpg"><h3>Rahul Kumar</h3><p>Assistant Chef</p></div>
    <div class="admin-card"><img src="images/admin4.jpg"><h3>Mary Joseph</h3><p>HR Manager</p></div>
    <div class="admin-card"><img src="images/admin5.jpg"><h3>Karthik Raj</h3><p>Inventory Manager</p></div>
    <div class="admin-card"><img src="images/admin6.jpg"><h3>Jennifer Thomas</h3><p>Marketing Head</p></div>

</div>

<footer>
Designed and Developed by <b>Surya P (212224230280)</b>
</footer>

</body>
</html>
```

### contact.html :

```html
<!DOCTYPE html>
<html>
<head>
    <title>Contact Us - Good Kitchen</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header><h1>Contact Us</h1></header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="contact-box">
    <h2>Little Lemon Restaurant</h2>
    <p>123 Food Street,<br>Coimbatore, Tamil Nadu</p>

    <p><b>Phone:</b> +91 092788853</p>
    <p><b>Email:</b> suryapandiaraj10@gmail.com.com</p>
</div>

<footer>
Designed and Developed by <b>Surya P (212224230280)</b>
</footer>

</body>
</html>

```

### index.html :

```html
<!DOCTYPE html>
<html>
<head>
    <title>Good Kitchen Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <div class="logo">
        <img src="images/logo.png" alt="logo">
        <h1>Good Kitchen</h1>
    </div>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <img src="images/banner.jpg">
    <div class="banner-text">30% Off This Weekend</div>
    <div class="banner-desc">Enjoy our weekend special discount on all dishes. Taste freshness, quality and love.</div>
</div>

<div class="card-container">

    <div class="card">
        <img src="images/card1.jpg">
        <h3>Our New Menu</h3>
        <p>Try our exciting new menu with delicious dishes crafted fresh every day.</p>
    </div>

    <div class="card">
        <img src="images/card2.jpg">
        <h3>Book a Table</h3>
        <p>Reserve your seat and enjoy a peaceful dining experience.</p>
    </div>

    <div class="card">
        <img src="images/card3.jpg">
        <h3>Opening Hours</h3>
        <p>Mon–Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
    </div>

</div>

<footer>
Designed and Developed by <b>Surya P (212224230280)</b>
</footer>

</body>
</html>

```

### menu.html :

```html
<!DOCTYPE html>
<html>
<head>
    <title>Menu - Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header><h1>Our Menu</h1></header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="menu-grid">

    <!-- 12 items -->
    <div class="menu-item"><img src="images/dish1.jpg"><h3>Grilled Chicken</h3></div>
    <div class="menu-item"><img src="images/dish2.jpg"><h3>Paneer Tikka</h3></div>
    <div class="menu-item"><img src="images/dish3.jpg"><h3>Margherita Pizza</h3></div>
    <div class="menu-item"><img src="images/dish4.jpg"><h3>Veg Pasta</h3></div>
    <div class="menu-item"><img src="images/dish5.jpg"><h3>Chicken Biryani</h3></div>
    <div class="menu-item"><img src="images/dish6.jpg"><h3>Fish Fry</h3></div>
    <div class="menu-item"><img src="images/dish7.jpg"><h3>Caesar Salad</h3></div>
    <div class="menu-item"><img src="images/dish8.jpg"><h3>Mushroom Soup</h3></div>
    <div class="menu-item"><img src="images/dish9.jpg"><h3>Garlic Bread</h3></div>
    <div class="menu-item"><img src="images/dish10.jpg"><h3>Chocolate Cake</h3></div>
    <div class="menu-item"><img src="images/dish11.jpg"><h3>Strawberry Shake</h3></div>
    <div class="menu-item"><img src="images/dish12.jpg"><h3>Fruit Platter</h3></div>

</div>

<footer>
Designed and Developed by <b>Surya P (212224230280)</b>
</footer>

</body>
</html>

```

### style.css :

```css
/* GLOBAL STYLES */
:root {
    --primary: #2E4F4F;
    --secondary: #CBE4DE;
    --accent: #F9F5EB;
    --highlight: #E8C07D;
    --text: #1B1B1B;
}

body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: var(--accent);
    color: var(--text);
}

/* HEADER */
header {
    text-align: center;
    padding: 20px 0;
    background: var(--accent);
}

.logo img {
    width: 100px;
}

nav {
    background: var(--primary);
    padding: 15px 0;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 25px;
    font-size: 18px;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

/* BANNER */
.banner {
    width: 95%;
    margin: 20px auto;
    overflow: hidden;
    border-radius: 12px;
    color: white;
    position: relative;
}

.banner img {
    width: 100%;
    border-radius: 12px;
}

.banner-text {
    position: absolute;
    top: 20%;
    left: 5%;
    color: white;
    font-size: 28px;
    font-weight: bold;
}

.banner-desc {
    position: absolute;
    top: 35%;
    left: 5%;
    width: 50%;
    color: white;
    font-size: 16px;
}

/* HOME PAGE CARDS */
.card-container {
    display: flex;
    justify-content: space-around;
    margin: 30px;
}

.card {
    width: 30%;
    background: var(--secondary);
    padding: 20px;
    border-radius: 14px;
}

.card img {
    width: 100%;
    border-radius: 10px;
}

.card h3 {
    margin-top: 10px;
}

.card p {
    font-size: 14px;
}

/* MENU PAGE */
.menu-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    width: 90%;
    margin: auto;
}

.menu-item {
    background: var(--secondary);
    padding: 15px;
    border-radius: 10px;
    text-align: center;
}

.menu-item img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

/* ADMIN PAGE */
.admin-grid {
    width: 90%;
    margin: auto;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.admin-card {
    padding: 20px;
    text-align: center;
    background: var(--secondary);
    border-radius: 12px;
}

.admin-card img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
}

/* CONTACT PAGE */
.contact-box {
    width: 60%;
    margin: auto;
    background: var(--secondary);
    padding: 30px;
    border-radius: 14px;
    text-align: center;
    margin-top: 40px;
}

/* FOOTER */
footer {
    text-align: center;
    margin-top: 40px;
    padding: 15px;
    background: var(--primary);
    color: white;
}

```

## OUTPUT :

<img width="1893" height="1022" alt="image" src="https://github.com/user-attachments/assets/2b723771-c524-44af-b53c-6bcb91908627" />

<img width="1900" height="1025" alt="image" src="https://github.com/user-attachments/assets/77a9ff03-545e-41c9-8645-b051458f4712" />

<img width="1899" height="1031" alt="image" src="https://github.com/user-attachments/assets/1be5a5eb-6ff7-4c4d-a606-9b61d157db07" />

<img width="1919" height="743" alt="image" src="https://github.com/user-attachments/assets/6040cbda-4347-4efb-8c00-bfb170eff423" />


## RESULT :
The program for designing software company website using HTML and CSS is completed successfully.
