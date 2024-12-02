# Ex04 Places Around Me
# Date:02/12/2024
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

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
    <img  src="c:\\Users\\admin\\Pictures\\Screenshots\\Screenshot 2024-11-21 232924.png" usemap="#mymap">
    <map name="mymap">
        <area shape="rect" coords="534,132,700,229" title="Smoke Hub" href="file:///C:/Users/admin/Desktop/html/imap3.html">
        <area shape="rect" coords="159,542,325,639" title="Bajaj Insurance" href="file:///C:/Users/admin/Desktop/html/imap1.html">
        <area shape="rect" coords="646,302,899,448" title="Laptop service" href="file:///C:/Users/admin/Desktop/html/imap2.html">
    </map>
</body>
</html>

```

# OUTPUT

![Screenshot 2024-12-02 105439](https://github.com/user-attachments/assets/9854e649-7e43-498b-ac4e-e332a5adea2d)


# RESULT
The program for implementing image maps using HTML is executed successfully.
