### Ex02 Commercial Website
## Date: 17-08-2026
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
STEP 1
Create an HTML file (index.html)

STEP 2
Create a CSS file (style.css)

STEP 3
Include a navigation bar with links to different sections.

STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

STEP 5
Include social media links at the footer with copyright information.

STEP 6
Define global styles for fonts, colors, and layout.

STEP 7
Style the header, navigation bar, and sections.

STEP 8
Use Flexbox for layout design.

STEP 9
Add hover effects and transitions for interactivity.

STEP 10
Add Images and Media.

STEP 11
Use optimized images for a professional look.

STEP 12
Open the HTML file in a browser to check layout and functionality.

STEP 13
Fix styling issues and refine content placement.

STEP 14
Deploy the website.

STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StyleHub - Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>StyleHub</h1>
        <p>Your Fashion, Your Style</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">Account</a>
    </nav>

    <!-- Home -->
    <section id="home" class="hero">
        <div>
            <h2>Welcome to StyleHub</h2>
            <p>Discover the latest fashion at affordable prices.</p>
            <button>Shop Now</button>
        </div>
    </section>

    <!-- Products -->
    <section id="products">
        <h2>Our Products</h2>

        <div class="products">

            <div class="card">
                <img src="https://via.placeholder.com/250" alt="Dress">
                <h3>Designer Dress</h3>
                <p>₹1,499</p>
                <button>Buy Now</button>
            </div>

            <div class="card">
                <img src="https://via.placeholder.com/250" alt="Shoes">
                <h3>Stylish Shoes</h3>
                <p>₹1,999</p>
                <button>Buy Now</button>
            </div>

            <div class="card">
                <img src="https://via.placeholder.com/250" alt="Handbag">
                <h3>Hand Bag</h3>
                <p>₹999</p>
                <button>Buy Now</button>
            </div>

        </div>
    </section>

    <!-- About -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>
            StyleHub is an online fashion store providing quality products
            at affordable prices. We offer trendy clothing, shoes and
            accessories for everyone.
        </p>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: stylehub@gmail.com</p>
        <p>Phone: +91 98765 43210</p>
        <p>Chennai, Tamil Nadu</p>
    </section>

    <!-- Account -->
    <section id="account" class="account">
        <h2>User Account</h2>
        <input type="text" placeholder="Username">
        <input type="password" placeholder="Password">
        <button>Login</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow us on</p>
        <div class="social">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
        <p>© 2026 StyleHub. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
style.css
```
/* Global Style */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f5f5f5;
    color: #333;
}

/* Header */
header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 25px;
}

/* Navigation */
nav {
    display: flex;
    justify-content: center;
    gap: 30px;
    background-color: #444;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: #ffcc00;
}

/* Sections */
section {
    padding: 40px 10%;
    text-align: center;
}

section h2 {
    margin-bottom: 20px;
}

/* Hero */
.hero {
    background-color: #ddd;
    min-height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.hero h2 {
    font-size: 35px;
}

/* Button */
button {
    background-color: #222;
    color: white;
    border: none;
    padding: 10px 20px;
    margin-top: 10px;
    cursor: pointer;
    border-radius: 5px;
    transition: 0.3s;
}

button:hover {
    background-color: #ff9800;
}

/* Products - Flexbox */
.products {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

.card {
    background-color: white;
    width: 250px;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px #ccc;
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

.card img {
    width: 100%;
    border-radius: 8px;
}

.card h3 {
    margin-top: 10px;
}

/* About */
.about {
    background-color: #eee;
}

/* Account */
.account {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.account input {
    width: 300px;
    padding: 12px;
    margin: 5px;
    border: 1px solid #aaa;
    border-radius: 5px;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 25px;
}

.social {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin: 10px;
}

.social a {
    color: white;
    text-decoration: none;
}

.social a:hover {
    color: #ffcc00;
}

/* Responsive Design */
@media (max-width: 600px) {
    nav {
        flex-direction: column;
        align-items: center;
        gap: 10px;
    }

    .products {
        flex-direction: column;
        align-items: center;
    }
}
```
## OUTPUT

<img width="1600" height="697" alt="image" src="https://github.com/user-attachments/assets/1f59afb6-905d-4549-826b-0b28e1c18131" />

<img width="626" height="640" alt="WhatsApp Image 2026-08-17 at 3 10 16 PM" src="https://github.com/user-attachments/assets/36b79bf6-3a4e-43cb-b1a6-7f6fc4b0857a" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
