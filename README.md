# Ex.07 Restaurant Website
## Date:09-12-24

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

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Bites Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>Delicious Bites</h1>
            <p>Where Taste Meets Excellence</p>
        </div>
    </header>

    <nav class="navbar">
        <ul>
            <li><a href="about.html">About Us</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Welcome to Delicious Bites, the best place in town for gourmet food, cozy ambiance, and exceptional service.</p>
        </div>
    </section>

    <section id="menu" class="menu">
        <div class="container">
            <h2>Our Menu</h2>
            <div class="food-items">
                <div class="food-item">
                    <img src="pizza.jpg" alt="Pizza">
                    <h3>Delicious Pizza</h3>
                    <p>Starting at $10</p>
                </div>
                <div class="food-item">
                    <img src="burger.jpg" alt="Burger">
                    <h3>Juicy Burgers</h3>
                    <p>Starting at $8</p>
                </div>
                <div class="food-item">
                    <img src="pasta.jpg" alt="Pasta">
                    <h3>Creamy Pasta</h3>
                    <p>Starting at $12</p>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <ul>
                <li>Online Food Delivery</li>
                <li>Event Catering</li>
                <li>Dine-In with Ambiance</li>
            </ul>
        </div>
    </section>

    <footer id="contact" class="footer">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: info@deliciousbites.com</p>
            <p>Phone:8124672741 </p>
            <p>Address: 123 Gourmet Street, Food City</p>
            <p>Follow us on:
                <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">Twitter</a>
            </p>
        </div>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Delicious Bites</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>About Us</h1>
            <p>Get to know more about Delicious Bites.</p>
        </div>
    </header>

    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="services.html">Reservations</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <section class="about">
        <div class="container">
            <h2>Our Story</h2>
            <p>Founded in 2010, Delicious Bites started as a small family-owned restaurant, aiming to bring a unique blend of global cuisines to our community. Over the years, we've grown into a beloved dining spot for food lovers, offering a perfect combination of quality ingredients and culinary passion.</p>
            <h2>Our Vision</h2>
            <p>To be a hub for extraordinary culinary experiences, where every meal tells a story, and every customer becomes part of our family.</p>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Delicious Bites</p>
        </div>
    </footer>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Delicious Bites</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>About Us</h1>
            <p>Get to know more about Delicious Bites.</p>
        </div>
    </header>

    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="services.html">Reservations</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <section class="about">
        <div class="container">
            <h2>Our Story</h2>
            <p>Founded in 2010, Delicious Bites started as a small family-owned restaurant, aiming to bring a unique blend of global cuisines to our community. Over the years, we've grown into a beloved dining spot for food lovers, offering a perfect combination of quality ingredients and culinary passion.</p>
            <h2>Our Vision</h2>
            <p>To be a hub for extraordinary culinary experiences, where every meal tells a story, and every customer becomes part of our family.</p>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Delicious Bites</p>
        </div>
    </footer>
</body>
</html>

services.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Services - Delicious Bites</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>Our Services</h1>
            <p>Explore the variety of services we offer to make your dining experience exceptional.</p>
        </div>
    </header>

    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <section class="services">
        <div class="container">
            <h2>What We Offer</h2>
            <div class="service-item">
                <img src="dine in.jpg" alt="Dine-In" height="200" width="200">
                <h3>Dine-In Experience</h3>
                <p>Relax and enjoy a cozy, elegant atmosphere with a diverse menu, great service, and delicious food. Our dine-in experience is perfect for any occasion, from casual meals to special celebrations.</p>
            </div>
            <div class="service-item">
                <img src="food delivery.jpg" alt="Delivery" height="200" width="200">
                <h3>Food Delivery</h3>
                <p>Can’t make it to the restaurant? No worries! We offer fast and reliable food delivery right to your doorstep. Enjoy our dishes in the comfort of your home with just a click.</p>
            </div>
            <div class="service-item">
                <img src="catering.jpg" alt="Catering" height="200" width="200">
                <h3>Catering Services</h3>
                <p>Planning an event or a celebration? Our catering service brings delicious meals to your special event, ensuring that your guests enjoy the same quality food we serve at our restaurant.</p>
            </div>
            <div class="service-item">
                <img src="private dining.jpg" alt="Private Dining" height="200" width="200">
                <h3>Private Dining</h3>
                <p>For a more intimate dining experience, we offer private dining options for you and your guests. Ideal for business meetings, private parties, and family gatherings.</p>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Delicious Bites</p>
        </div>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Delicious Bites</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>Our Menu</h1>
            <p>Explore our mouth-watering dishes, crafted with love.</p>
        </div>
    </header>

    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="services.html">Reservations</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <section class="menu">
        <div class="container">
            <h2>Our Delicious Offerings</h2>
            <div class="food-items">
                <div class="food-item">
                    <img src="pizza.jpg" alt="Pizza">
                    <h3>Margherita Pizza</h3>
                    <p>$12</p>
                </div>
                <div class="food-item">
                    <img src="burger.jpg" alt="Burger">
                    <h3>Classic Cheeseburger</h3>
                    <p>$10</p>
                </div>
                <div class="food-item">
                    <img src="pasta.jpg" alt="Pasta">
                    <h3>Alfredo Pasta</h3>
                    <p>$14</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Delicious Bites</p>
        </div>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Delicious Bites</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>Contact Us</h1>
            <p>We'd love to hear from you!</p>
        </div>
    </header>

    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="services.html">Reservations</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <section class="contact">
        <div class="container">
            <h2>Get in Touch</h2>
            <form action="#" method="POST" class="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Send Message</button>
            </form>
            <h3>Our Address</h3>
            <p>123 Gourmet Street, Food City</p>
            <p>Email: info@deliciousbites.com</p>
            <p>Phone:8124672741 </p>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Delicious Bites</p>
        </div>
    </footer>
</body>
</html>


```

## OUTPUT:

![alt text](<Screenshot (63).png>)
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)
![alt text](<Screenshot (67).png>)
![alt text](<Screenshot (68).png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
