# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ABC Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav {
      background-color: #444;
      text-align: center;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffd700;
    }
    section {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin: 20px;
    }
    .product {
      background: white;
      width: 250px;
      margin: 10px;
      padding: 15px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 0 10px gray;
    }
    .product img {
      width: 100%;
      height: 200px;
      border-radius: 10px;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>ABC Commercial Store</h1>
    <p>Your One-Stop Online Shop</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">About Us</a>
    <a href="#">Contact</a>
  </nav>

  <section>
    <div class="product">
      <h3>Smartphone</h3>
      <p>Price: ₹25,000</p>
    </div>
    <div class="product">
      <h3>Laptop</h3>
      <p>Price: ₹65,000</p>
    </div>
    <div class="product">
      <h3>Headphones</h3>
      <p>Price: ₹3,000</p>
    </div>
  </section>

  <footer>
    <p>© 2025 ABC Store | All Rights Reserved</p>
  </footer>
</body>
</html>


```

## OUTPUT
<img width="1917" height="907" alt="image" src="https://github.com/user-attachments/assets/e9187ecf-f55e-414f-9eb5-3b16bbc3bef0" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
