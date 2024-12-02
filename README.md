# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:

1.HOME.HTML
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TATEL RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('c:/Users/admin/Downloads/BACKGROUND.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white; 
        }

        header {
            background-color:  #0083ca; 
            padding: 20px;
            color: white;
            text-align: center;
        }

        .logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .logo-container img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            margin-right: 10px;
        }

        .logo-container h3 {
            margin: 0;
        }

        header nav ul {
            list-style-type: none;
            margin: 20px 0 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        header nav ul li {
            margin-right: 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: rgba(0, 0, 0, 0.6);
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.7);
        }

        .discount-section {
            text-align: center;
            padding: 50px 20px;
            background-color: rgba(255, 255, 255, 0.9);
            color: #333;
        }

        .discount-section h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        .discount-food {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        .discount-food img {
            width: 500px;
            height: 500px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .discount-banner {
            background-color: #FF5733;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color:  #0083ca; 
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo-container">
            <img src="c:/Users/admin/Downloads/logo-ajustes-cookies-300x300.png" alt="Restaurant Logo">
            <h3>TATEL RESTAURANT</h3>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="aboutus.html">About Us</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="hero">
        <h1>Welcome to TATEL Restaurant</h1>
        <p>Experience the finest culinary delights.</p>
    </section>

    <section class="discount-section">
        <h2>Special Offer</h2>
        <div class="discount-food">
            <img src="c:/Users/admin/Pictures/Screenshots/Screenshot 2024-11-29 112305.png" alt="Special Dish">
            <p class="discount-banner">Enjoy up to 25% Off on Our Chef's Special Dish!</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 TATEL Restaurant | All Rights Reserved</p>
    </footer>
</body>
</html>
```

2.MENU.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu | TATEL RESTAURANT</title>
    <style>
    
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('c:/Users/admin/Downloads/BACKGROUND.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            
        }

        header {
            background-color:  #0083ca;
            padding: 20px;
            color: white;
        }

        header nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header nav ul li {
            display: inline;
            margin-right: 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .menu {
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.9); 
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            border-radius: 10px;
            margin: 20px auto;
            max-width: 1200px;
        }

        .menu h1 {
            text-align: center;
            width: 100%;
            margin-bottom: 20px;
            font-size: 24px;
            color: #f7e9e9;
        }
        .menu h2 {
            text-align: center;
            width: 100%;
            margin-bottom: 20px;
            font-size: 24px;
            color: #000000;

        }

        .menu-item {
            margin: 15px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 200px;
            text-align: center;
            background-color: #e9e9e9;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100%;
            height: 150px;
            border-radius: 8px;
            object-fit: cover;
            margin-bottom: 10px;
        }

        .menu-item h2 {
            font-size: 18px;
            margin: 10px 0;
            
        }

        .menu-item span {
            font-weight: bold;
            color: #007BFF;
            display: block;
            margin-top: 5px;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #0083ca;
            color: white;
            margin-top: 20px;
        }
    </style>

</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="aboutus.html">About Us</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1> 

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\chicken biryani.jpg" alt="Chicken Biryani">
            <h2>Chicken Biryani</h2>
            <span>RS-120</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Best-Mutton-Biryani-Recipe.jpg" alt="Mutton Biryani">
            <h2>Mutton Biryani</h2>
            <span>RS-220</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\butter-chicken.jpg" alt="Butter Chicken">
            <h2>Butter Chicken</h2>
            <span>RS-150</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Tandoori.jpg" alt="Tandoori Chicken">
            <h2>Tandoori Chicken</h2>
            <span>RS-270</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Grill.jpg" alt="Grill Chicken">
            <h2>Grill Chicken</h2>
            <span>RS-250</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Pasta.jpg" alt="Pasta">
            <h2>Pasta</h2>
            <span>RS-150</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Burger.jpg" alt="Burger">
            <h2>Burger</h2>
            <span>RS-170</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Pizza.png" alt="Pizza">
            <h2>Pizza</h2>
            <span>RS-350</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Chicken Gravy.jpg" alt="Chettinad Chicken Gravy">
            <h2>Chettinad Chicken Gravy</h2>
            <span>RS-180</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Kothu-Parotta.jpg" alt="Kothu Parotta">
            <h2>Kothu Parotta</h2>
            <span>RS-120</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Chicken-Shawarma-3.jpg" alt="Shawarma">
            <h2>Shawarma</h2>
            <span>RS-80</span>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Noodles.jpg" alt="Chicken Noodles">
            <h2>Chicken Noodles</h2>
            <span>RS-180</span>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 TATEL Restaurant | All Rights Reserved</p>
    </footer>
</body>
</html>
```
3.ABOUTUS.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us | TATEL RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('c:/Users/admin/Downloads/BACKGROUND.jpg') no-repeat center center fixed;
            background-size: cover;
            color: rgb(0, 0, 0);
        }

        header {
            background-color:  #0083ca;
            padding: 20px;
            color: white;
        }

        header nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header nav ul li {
            display: inline;
            margin-right: 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .about {
            padding: 20px;
            background-color: #ffffff;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            border-radius: 10px;
            margin: 20px auto;
            max-width: 1200px;
        }

        .about h1,
        .about h2 {
            text-align: center;
            width: 100%;
            margin-bottom: 20px;
            font-size: 24px;
             color: #333;
        }

        .chef-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .chef {
            text-align: center;
            width: 150px;
        }

        .chef img {
            width: 190px;
            height: 190px;
            object-fit: cover; 
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 10px;
        }

        .chef p {
            margin: 0;
            font-weight: bold;
            color: #007BFF;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #0083ca;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="aboutus.html">About Us</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="about">
        <h1>About TATEL Restaurant</h1>
        <p>TATEL is a fine dining restaurant committed to delivering an exceptional culinary experience with every dish. Our chefs use only the finest ingredients to create delectable meals that will transport you to another world.</p>
        
        <h2>Our Mission</h2>
        <p>To provide a memorable dining experience while offering a fusion of exquisite tastes, high-end service, and a welcoming ambiance.</p>
        
        <h2>Meet Our Chefs</h2>
        <div class="chef-grid">
            <div class="chef">
                <img src="c:\Users\admin\Downloads\unnamed.jpg" alt="Chef 1">
                <p>Chef Damodaran</p>
            </div>
            <div class="chef">
                <img src="c:\Users\admin\Downloads\channels4_profile.jpg" alt="Chef 2">
                <p>Chef Venkatesh Bhatt</p>
            </div>
            <div class="chef">
                <img src="c:\Users\admin\Downloads\CHEf 3.avif" alt="Chef 3">
                <p>Chef Sanjeev Kapoor</p>
            </div>
            <div class="chef">
                <img src="c:\Users\admin\Downloads\chef.jpg" alt="Chef 4">
                <p>Chef Madhampatty Rangaraj</p>
            </div>
            <div class="chef">
                <img src="c:\Users\admin\Downloads\Chef 6.webp" alt="Chef 5">
                <p>Chef Dheena</p>
            </div>
            <div class="chef">
                <img src="c:\Users\admin\Downloads\Chef 7.jpg" alt="Chef 6">
                <p>Chef Koushik</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 TATEL Restaurant | All Rights Reserved</p>
    </footer>
</body>
</html>
```

4.CONTACTUS.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | TATEL RESTAURANT</title>
</head>
<body style="font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4;">
    <header style="background-color:  #0083ca; padding: 20px; color: white;">
        
        <nav>
            <ul style="list-style-type: none; margin: 0; padding: 0; text-align: center;">
                <li style="display: inline; margin-right: 20px;"><a href="home.html" style="color: white; text-decoration: none; font-size: 18px;">Home</a></li>
                <li style="display: inline; margin-right: 20px;"><a href="menu.html" style="color: white; text-decoration: none; font-size: 18px;">Menu</a></li>
                <li style="display: inline; margin-right: 20px;"><a href="aboutus.html" style="color: white; text-decoration: none; font-size: 18px;">About Us</a></li>
                <li style="display: inline; margin-right: 20px;"><a href="contactus.html" style="color: white; text-decoration: none; font-size: 18px;">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact" style="padding: 20px; background-color: #ffffff;">
        <h1 style="margin-bottom: 20px;">Contact Us</h1>
        <p style="margin-bottom: 10px;">If you have any questions or would like to make a reservation, feel free to reach out to us:</p>
        <p style="margin-bottom: 10px;"><strong>Email:</strong> info@tatelrestaurant.com</p>
        <p style="margin-bottom: 10px;"><strong>Phone:</strong> +91 8248721748</p>
        <p><strong>Address:</strong> 123 cris street,RS puram ,Coimbatore</p>
    </section>

    <section class="review" style="padding: 20px; background-color: #ffffff; margin-top: 20px;">
        <h1 style="margin-bottom: 20px; text-align: center;">Leave a Review</h1>
        <form action="#" method="post" style="max-width: 500px; margin: 0 auto;">
            <label for="name" style="display: block; margin-bottom: 10px; font-weight: bold;">Name:</label>
            <input type="text" id="name" name="name" placeholder="Your Name" required 
                style="width: 100%; padding: 10px; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px;">

            <label for="phone" style="display: block; margin-bottom: 10px; font-weight: bold;">Phone Number:</label>
            <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required 
                style="width: 100%; padding: 10px; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px;">

            <label for="review" style="display: block; margin-bottom: 10px; font-weight: bold;">Your Review:</label>
            <textarea id="review" name="review" rows="5" placeholder="Write your review here..." required 
                style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px;"></textarea>

            <button type="submit" style="display: block; width: 100%; padding: 10px; background-color: #007BFF; color: white; border: none; border-radius: 5px; font-size: 16px; font-weight: bold; cursor: pointer; margin-top: 20px;">Submit Review</button>
        </form>
    </section>

    <footer style="text-align: center; padding: 10px; background-color: #0083ca; color: white; margin-top: 20px;">
        <p>&copy; 2024 TATEL Restaurant | All Rights Reserved</p>
    </footer>
</body>
</html>
```
# OUTPUT:

HOME
![screencapture-file-C-Users-admin-Desktop-HTML2-home-html-2024-12-02-14_17_43](https://github.com/user-attachments/assets/dcd36eae-c670-4339-be02-910e58103508)

MENU
![screencapture-file-C-Users-admin-Desktop-HTML2-menu-html-2024-12-02-14_18_24](https://github.com/user-attachments/assets/c27c24bf-bdf8-40e3-9dd6-f00ea5bde860)

ABOUTUS
![screencapture-file-C-Users-admin-Desktop-HTML2-aboutus-html-2024-12-02-14_18_55](https://github.com/user-attachments/assets/16ffe534-2327-4512-834a-b8fdb82f5970)

CONTACTUS
![screencapture-file-C-Users-admin-Desktop-HTML2-contactus-html-2024-12-02-14_19_42](https://github.com/user-attachments/assets/5f2c3382-2bb4-47af-b30c-d46488be016c)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
