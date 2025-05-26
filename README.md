# Ex04 Places Around Me

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
imagemap.html
<html>
    <head>imageapp</head>
    <title>
        imageapp
    </title>
    <body>
<img src="Screenshot (10).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="bakery" title="bakery" href="paary bakery.html" coords="820,328,52" shape="circle">
    <area target="" alt="theater" title="theater" href="sri lakshmi theater.html" coords="781,546,652,481" shape="rect">
    <area target="" alt="park" title="park" href="children park.html" coords="366,444,523,442,447,590" shape="poly">
</map>
    </body>
</html>

paary bakery.html

<html>
<head>
    <title>PARRY BAKERY</title>
</head>
<body bgcolor="pink">

    <h1 align="center">
        <font color="red">PARRY BAKERY</font>
    </h1>
    <hr size="3" color="red">

    <p align="justify">
        Parry Bakery is a well-known bakery located in Arani, Tamil Nadu. It has been serving fresh and delicious 
        baked goods for many years, and is a favorite among the local residents.
        <br><br>

        <b>Popular Items:</b><br><br>

        <b>Breads and Buns:</b> Soft milk bread and sweet buns are some of the best-selling items.<br><br>

        <b>Puffs and Pastries:</b> Crispy vegetable and chicken puffs, along with cream-filled pastries, are loved by all age groups.<br><br>

        <b>Cakes:</b> Birthday cakes, anniversary cakes, and custom-themed cakes are available in chocolate, vanilla, butterscotch, and more.<br><br>

        <b>Cookies and Snacks:</b> The bakery also offers a wide variety of biscuits and traditional Indian snacks.<br><br>

        <b>Customer Experience:</b> Known for affordable pricing, fresh quality, and friendly staff. It’s a regular stop for students, families, and party planners in town.
    </p>

</body>
</html>

children park.html

<html>
<head>
    <title>SRI VENKATRAMAN PARK - ARNI</title>
</head>
<body bgcolor="lightblue">

    <h1 align="center">
        <font color="red">VENKATRAMAN PARK</font>
    </h1>
    <hr size="3" color="black">

    <p align="justify">
        Venkatraman Park is a peaceful and well-known recreational spot located in Arni, Tamil Nadu. It serves as a great place 
        for families, children, and morning walkers to relax and enjoy nature within the town.
        <br><br>

        <b><font color="darkgreen">Park Highlights:</font></b><br><br>

        <b>Greenery:</b> The park is filled with trees, plants, and flowering bushes, providing fresh air and a pleasant environment.<br><br>

        <b>Walking Path:</b> A neat and well-laid walking track is available for morning joggers and evening strollers.<br><br>

        <b>Children's Play Area:</b> Includes swings, slides, and other fun play equipment for kids.<br><br>

        <b>Benches & Sitting Areas:</b> Plenty of seating space is provided for elders and families to relax.<br><br>

        <b>Location:</b> Easily accessible from different parts of Arni, it is a favorite spot for spending quiet evenings and weekends.<br><br>

        <b>Cleanliness:</b> The park is generally well-maintained by the local municipality, encouraging people to visit regularly.
    </p>

</body>
</html>


sri lakshmi theater.html

<html>
<head>
    <title>SRI LAKSHMI THEATER - ARNI</title>
</head>
<body bgcolor="lavender">

    <h1 align="center">
        <font color="red">SRI LAKSHMI THEATER</font>
    </h1>
    <hr size="3" color="violet">

    <p align="justify">
        Sri Lakshmi Theater is one of the most popular cinema halls in Arni, Tamil Nadu. It is known for providing 
        a great movie-watching experience with good sound and picture quality. The theater attracts both local residents 
        and visitors from nearby areas.
        <br><br>

        <b>Features and Facilities:</b><br><br>

        <b>Screen & Sound:</b> Equipped with a digital screen and modern sound system for an enhanced cinematic experience.<br><br>

        <b>Seating:</b> Comfortable seating with decent leg space. The theater is divided into different classes for ticket pricing.<br><br>

        <b>Movies:</b> Tamil, Telugu, and Hindi movies are regularly screened, including the latest blockbusters.<br><br>

        <b>Snacks:</b> A small canteen is available with popcorn, beverages, and snacks at affordable prices.<br><br>

        <b>Location:</b> Located conveniently within the town, making it easily accessible by walk or local transport.<br><br>

        <b>Audience Experience:</b> Known for its decent maintenance and budget-friendly ticket rates, Sri Lakshmi Theater remains a favorite 
        weekend destination for movie lovers in Arni.
    </p>

</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/b6fccdc8-c429-4ee0-a825-79ae92c81246)
![image](https://github.com/user-attachments/assets/65d23f55-f89d-4c16-970b-742609202f7c)
![image](https://github.com/user-attachments/assets/a488dd9b-3cfa-46be-8f70-3a5ba7bfab2e)
![image](https://github.com/user-attachments/assets/9c61b0ae-b687-404d-868c-80ec7169bc03)

## RESULT
The program for implementing image maps using HTML is executed successfully.
