# Ex04 Places Around Me
# Date:18-05-2025
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
<html>
    <head>
        <title>my map</title>
    </head>
    <body>
        <img src="c:\Users\admin\Downloads\1.PNG.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="station" title="RAILWAY STATION" href="1.html" coords="669,643,853,716" shape="rect">
    <area target="" alt="medical" title="GOVT HOSPITAL" href="2.html" coords="128,881,377,954" shape="rect">
    <area target="" alt="store" title="RELIANCE DIGITAL MARKET" href="3.html" coords="1101,122,1309,214" shape="rect">
    <area target="" alt="hotel" title="SINDHU TOWERS" href="4.html" coords="150,29,348,85" shape="rect">
    <area target="" alt="chittoor" title="CHITTOOR" href="5.html" coords="743,478,932,557" shape="rect">
</map>
    </body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chittoor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Native</h1>
    
</header>



<div class="container">
    <h2>About this place</h2>

    <div class="product">
        <p>Chittoor, located in the southeastern state of Andhra Pradesh, is known for its rich cultural heritage and proximity to the famous Tirupati temple. The region is also an important agricultural hub, especially renowned for mango and sugarcane cultivation.</p>
    </div>

    
    
</div>


</body>
</html>
                                                                                                                                                                  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Medical</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to GOVERNMENT HOSPITAL </h1>
    
</header>



<div class="container">
    <h2>The Medical Shop</h2>

    <div class="product">
        <p>Chittoor Government Hospital, located on Church Street in Thotapalyam, is a prominent healthcare facility in Andhra Pradesh. Managed by the Apollo Group of Hospitals since 2016 under a 33-year lease, it has undergone significant upgrades, including increasing its bed capacity from 310 to 850 and establishing over 66 ICU ward</p>
    </div>

    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Thotapalyam,church road</p>
    <p><strong>Phone:</strong>9264123210</p>
</div>


</body>
</html>
                                                                                                                                                                   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Super Market</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Reliance Digital Market</h1>
    
</header>



<div class="container">
    <h2>About Digital Market</h2>

    <div class="product">
        <p>Reliance SMART Superstore in Chittoor offers a comprehensive shopping experience with a wide range of groceries, homeware, and fashion items. Located on Vellore Road near Subramanyaswamy Temple, it is open daily from 7:00 AM to 9:00 PM, providing convenient access to essential products for the local community</p>
    </div>

    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Palamner Road , chittoor</p>
    <p><strong>Phone:</strong>765836120</p>
    
</div>


</body>
</html>
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
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Sindhu Towers</h1>
    
</header>



<div class="container">
    <h2>Restaurant Special Dish</h2>

    <div class="product">
        <p>Pizza, from Italy. Ramen, from Japan. Burger, from the United States. Paella, from Spain.</p>
    </div>

    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Gandhi Road, Chittoor</p>
    <p><strong>Phone:</strong>7658362120</p>
    
</div>


</body>
</html>
                                                                                                                                                                <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Railway Station</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to the Railway Station</h1>
    
</header>



<div class="container">
    <h2>About Railway Station</h2>

    <div class="product">
        <p>Chittoor Railway Station (station code: CTO) is a B-category station situated on the Gudur–Katpadi branch line in Andhra Pradesh</p>
    </div>
    
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Railway station , Chittoor</p>
    <p><strong>Phone:</strong>765836120</p>

    
    
</div>


</body>
</html>
```
# OUTPUT
![Screenshot 2025-05-18 202541](https://github.com/user-attachments/assets/c7dab562-a4a6-4fc9-b0c1-5c33eb65bcdb)
![Screenshot 2025-05-18 204010](https://github.com/user-attachments/assets/28d3f72e-510f-44de-878d-644606705b30)
![Screenshot 2025-05-18 204033](https://github.com/user-attachments/assets/0ebfc4cf-8724-49b6-b363-604fbab24c64)
![Screenshot 2025-05-18 204045](https://github.com/user-attachments/assets/ffeda5cf-540b-480c-b0b9-3bc21a5f63da)
# RESULT
The program for implementing image maps using HTML is executed successfully.
