# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
MAIN 

<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body class="text-center">
        <nav class="navbar navbar-expand-lg navbar-light bg-warning">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="#">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href="C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <h1>SHREYA PHARMACY</h1>
        <img src="C:\Users\admin\Downloads\pharmacy.jpeg">

<footer class="bg-light text-center py-3">
<p>Designed and Developed by S.RAMITHA CHOWDARY</p>
</footer>
</body>
</html>

PRODUCT 

<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-warning">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="#">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href="C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
       
        <div class="row">
            <div class="col-12">
                <h2>Contact Us</h2>
                <form>
                    <div class="form-group">
                        <label for="name">Your Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                    <div class="form-group">
                        <label for="email">Email address</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter email">
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea class="form-control" id="message" rows="3" placeholder="Your message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
    </div>
    <footer class="bg-light text-center py-3">
        <p>Designed and Developed by S.RAMITHA CHOWDARY</p>
    </footer>    
    </body>

</html>

HOME 

<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body class="text-center">
        <nav class="navbar navbar-expand-lg navbar-light bg-success">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="C:\Users\admin\home.html">AROGYA Pharmacy</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href=" C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
                
            </div>
        </nav>
        <div class="row">
            <div class="col">
                <br><br>
                <h1>Welcome to Our Pharmacy</h1>
                <p>We provide a variety of pharmaceutical products and services. Your health is our priority!</p>
            </div>
        </div>
        <img  src="c:\Users\Sashmitha sree\Pictures\Saved Pictures\istockphoto-1135284188-612x612.jpg">
        <footer class="bg-light text-center py-3">
            <p>Designed and Developed by S.RAMITHA CHOWDARY</p>
        </footer>
    </body>

    </html>

    ABOUT 

    <html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-success">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="C:\Users\admin\home.html">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href=" C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                            <a class="nav-link text-white" 
                        </li>
                        <li class="naBOUT</a>v-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
           
                <p class="Toggle text">
                    About Us<br>

Welcome to arogya Pharmacy, your trusted partner in health and wellness. Established in 2020, we are dedicated to providing high-quality pharmaceutical care, personalized service, and expert guidance to ensure the well-being of our customers.
           
<br><br><br>
Who We Are<br>
At arogya pharmacy, we are more than just a pharmacy. We are a team of experienced healthcare professionals committed to improving the quality of life for our community. Our staff includes licensed pharmacists, knowledgeable technicians, and friendly support staff who are passionate about meeting your healthcare needs.
<br><br><br>
Our Mission<br>
Our mission is to deliver reliable, affordable, and accessible healthcare solutions tailored to each customer. We believe in fostering trust and building long-term relationships with our clients by consistently exceeding their expectations.
<br><br><br>
What We Offer<br>
Prescription Services: Fast and accurate prescription filling with expert advice.
Over-the-Counter Products: A wide range of health and wellness products, including vitamins, supplements, and personal care items.
Consultation Services: One-on-one consultations for medication management, health screenings, and wellness advice.
Home Delivery: Convenient and timely delivery of your medications right to your doorstep.
Specialty Medications: Support for complex conditions with specialized medications and care programs.
<br><br><br>Why Choose Us?<br>
Customer-Centric Care: Your health and satisfaction are our top priorities.
Expert Guidance: Our pharmacists provide personalized advice to help you make informed healthcare decisions.
Quality Assurance: We adhere to the highest standards of safety and quality in everything we do.
Community Commitment: We are proud to be an integral part of our community, supporting local initiatives and wellness programs.
<br><br><br>Our Vision<br>
We envision a healthier future where everyone has access to exceptional pharmaceutical care. By embracing innovation and staying at the forefront of the healthcare industry, we aim to be your lifelong partner in health.
<br><br><br>
Thank you for choosing arogya Pharmacy. We look forward to serving you and making a positive impact on your health journey.
                </p>
            </div>
        </nav>
        <footer class="bg-light text-center py-3">
            <p>Designed and Developed by S.RAMITHA CHOWDARY</p>
        </footer>
    </body>

</html>
```

# OUTPUT:

<img width="1738" height="1140" alt="image" src="https://github.com/user-attachments/assets/da3e9bc2-3221-4eed-8ab0-12ca8cd386c0" />

<img width="1646" height="1125" alt="image" src="https://github.com/user-attachments/assets/a25f95e7-82a4-4b27-a72a-1265d291ab4e" />

<img width="1717" height="1113" alt="image" src="https://github.com/user-attachments/assets/71199e44-e734-42cb-b5a1-64bc752512f5" />

<img width="1918" height="1135" alt="image" src="https://github.com/user-attachments/assets/625dc4b2-3fb3-4f4f-bc36-c36b94269468" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
