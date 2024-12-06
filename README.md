# Ex04 Places Around Me
# Date:26/10/2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE

```python

Imagemap code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
    <img  src="/static/Screenshot 2024-11-21 232924.png" usemap="#mymap">
    <map name="mymap">
        <area shape="rect" coords="534,132,700,229" title="Smoke Hub" href="file:///C:/Users/admin/Desktop/html/imap3.html">
        <area shape="rect" coords="159,542,325,639" title="Bajaj Insurance" href="file:///C:/Users/admin/Desktop/html/imap1.html">
        <area shape="rect" coords="646,302,899,448" title="Laptop service" href="file:///C:/Users/admin/Desktop/html/imap2.html">
        <area shape="rect" coords="1269,77,1517,213" title="Hi tech plus" href="file:///C:/Users/admin/Desktop/html/imap4.html">
        <area shape="rect" coords="0,210,261,364" title="Restaurant" href="file:///C:/Users/admin/Desktop/html/kitchen%20menu.html">
    </map>
</body>
</html>

Website:1 CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Finance Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ece9e9;
            text-align: center;
        }

        header {
            background-color: #044d99;
            color: white;
            padding: 20px 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        h1, h2 {
            color: #000000;
        }

        .description {
            font-size: 1.2em;
            color: #333;
            margin: 20px 0;
        }

        .contact-info {
            margin-top: 30px;
            font-size: 1.1em;
        }

        .contact-info a {
            color: #004d99;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #044d99;
            color: white;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>WELCOME TO BAJAJ FINANCE</h1>
    </header>

    <div class="container">
        <img src="/static/bajaj.png" width="300">

        <div class="description">
            <h2>About Bajaj Finance</h2>
            <p>At Bajaj Finance, we specialize in providing a wide range of financial services designed to help individuals and businesses achieve financial success. Our team of experts offers tailored solutions for investments, loans, asset management, and wealth planning. With a strong focus on customer satisfaction, we pride ourselves on offering trustworthy and reliable financial advice that drives results.</p>
            <p>Whether you're looking to secure your future, plan for retirement, or manage your finances, Bajaj Finance is here to support you every step of the way. Our mission is to empower our clients with the knowledge and resources to make informed decisions and achieve financial freedom.</p>
        </div>

        <div class="contact-info">
            <h2>Contact Us</h2>
            <p>Office Location: 456 Financial Street,Porur,Chennai,Tamilnadu,India</p>
            <p>Phone:+9786577285</p>
            <p>Email:bajajfinance@gmail.com</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 BAJAJ Finance | All rights reserved</p>
    </footer>
</body>
</html>

Website:2 CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laptop Service Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ece4e4;
            text-align: center;
        }

        header {
            background-color: #c9a9a9;
            color: white;
            padding: 20px 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        h1, h2 {
            color: #9b2424;
        }

        .description {
            font-size: 1.2em;
            color: #333;
            margin: 20px 0;
        }

        .contact-info {
            margin-top: 30px;
            font-size: 1.1em;
        }

    </style>
</head>
<body>
    <header>
        <h1>GBS SYSTEMS AND LAPTOP SERVICES</h1>
    </header>

    <div class="container">
        <img src="/static/gbs.jpg" width="700">

        <div class="description">
            <h2>About Our Services</h2>
            <p>Welcome to GBS Laptop Service, your trusted partner for all your laptop repair and maintenance needs. Whether you're facing a hardware issue, software problem, or need a complete laptop tune-up, our experienced technicians are here to help. We provide expert repairs for all major laptop brands, ensuring that your device runs like new again.</p>
            <p>Our services include screen replacements, battery replacement, motherboard repairs, virus removal, data recovery, operating system installation, and much more. We offer affordable, reliable, and fast services so you can get back to work or entertainment with minimal downtime.</p>
        </div>

        <div class="contact-info">
            <h2>Contact Us</h2>
            <p>Location:Arcot road,Porur,Chennai,Tamilnadu</p>
            <p>Phone:+9746518877</p>
            <p>Email:gbslaptopservice@gmail.com</p>
        </div>
    </div>
</body>
</html>
      
Website:3 CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            text-align: center;
        }

        header {
            background-color: #ffffff;
            color: white;
            padding: 10px 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        h1, h2 {
            color: #090808;
        }

        .description {
            font-size: 1.2em;
            color: #555;
            margin: 20px 0;
        }

        .contact-info {
            margin-top: 30px;
            font-size: 1.1em;
        }

        .contact-info a {
            color: #333;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #ffffff;
            color: white;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Restaurant</h1>
    </header>

    <div class="container">
        <img src="/static/smoke.png" width="500"   alt="Restaurant Image">

        <div class="description">
            <h2>About Us</h2>
            <p>At our restaurant, we serve a variety of delicious dishes made from the freshest ingredients. Our chefs are passionate about creating mouthwatering meals for all tastes. Whether you're here for a quick bite or a special celebration, we ensure a memorable dining experience.</p>
        </div>

        <div class="contact-info">
            <h2>Contact Us</h2>
            <p>Location: 123 Main Street, City, Country</p>
            <p>Phone:+767 787 9908</p>
            <p>Email:smokehub@gmail.com</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Our Restaurant | All rights reserved</p>
    </footer>
</body>
</html>

Website:4 CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Gym</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 15px 20px;
            text-align: center;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        .images {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        .images img {
            width: 300px;
            height: 200px;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to HI TECH PLUS</h1>
    </header>
    <div class="container">
        <p>At Fitness Gym, we offer state-of-the-art equipment, expert trainers, and personalized workout plans to help you achieve your fitness goals.</p>
        <p>Our gym is equipped with state-of-the-art cardio machines, free weights, and strength training equipment to suit any workout style. 
        For those who prefer a dynamic group setting, we offer a variety of classes, including yoga, Zumba, spinning, and HIIT, led by certified instructors who will motivate and inspire you.
        Looking for personalized guidance? Our experienced personal trainers provide customized workout plans tailored to your fitness goals, whether you’re building strength, improving endurance, or enhancing flexibility.</p>
        <div class="images">
            <img src="/static/gym1.jpg">
            <img src="/static/gym2.jpg">
            <img src="/static/gym3.jpg">
        </div>
    </div>
    <footer>
        <p>Contact Us: +123 456 7890 | hitechplus@example.com</p>
        <p>Visit Us: 123 Fitness Street, Workout City</p>
    </footer>
</body>
</html>

Website:5 CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>restaurant</title>
</head>
<style>
    body{
        background-image: url("c:\\Users\\admin\\Downloads\\main.webp");
    }
    .ref{
        position: absolute;
        font-size: 400%;
        top: 55%;
        left: 5%;
    }
    .ref1 a{
        font-size: 142%;
        position: relative;
        top: 420px;
    }
    header{
        font-size: 568%;
    }
    footer{
        background-color: black;
        position: relative;
        top: 615px;
        font-size: 70px;
        left:8px
    }

</style>
<body>
    <center>
        <header style="color: rgb(245, 59, 59);">
            ℌѦʊη†℮∂ ⚠️ ґ℮s†Ѧʊґ℮η†
        </header>
        <div class="ref">
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/home.html" style="color: aliceblue;">HOME</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/menu.html" style="color: rgb(255, 0, 34);">MENU</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/about.html" style="color: aliceblue;">ABOUT</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/contact.html" style="color: rgb(255, 0, 34);">CONTACT</a>
        <a>†</a>
        </div>
        <footer style="color: rgb(255, 255, 255);">
            KISHORE
        </footer>
    </center>
   
</body>
</html>
 
```

# OUTPUT
WEBSITE:1
![Screenshot 2024-12-07 001200](https://github.com/user-attachments/assets/b794778e-42a2-4d40-b744-045f824d33c8)
WEBSITE:2
![Screenshot 2024-12-07 001215](https://github.com/user-attachments/assets/49563717-d53d-4ef9-9b5b-aafffa6bdaef)
WEBSITE:3
![Screenshot 2024-12-07 001236](https://github.com/user-attachments/assets/c884b8f1-19cf-4297-89b8-0fa685d10d85)
WEBSITE:4
![Screenshot 2024-12-07 001251](https://github.com/user-attachments/assets/f0207cfc-52ea-4a42-b6dc-00f3c4296a60)
WEBSITE:5
![Screenshot 2024-12-07 001303](https://github.com/user-attachments/assets/67b7e506-4ff2-4525-bdf6-457ddb5e3030)
# RESULT
The program for implementing image maps using HTML is executed successfully.
