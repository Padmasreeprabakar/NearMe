# Ex04 Places Around Me
## Date: 2.05.2025

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
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <center>
        <h1 >
        <font color="lightblue" >AYAPPAKAM</font>
        </h1>
        <h3 > <font color ="black" > AARON MARIYAN A    REG NO: 212224040004 </font></h3>
        
            <img src="Screenshot 2025-05-02 153627.png" usemap="#MyCity" height ='510' width="1400">
            <map name="MyCity">
                <area shape="rect" coords="100,100,900,900" href="home.html" title="MY HOME">
                <area shape="rect" coords="34,61,187,153" href="hall.html" title="SELVI MAHAL">
                <area shape="rect" coords="1286,232,1414,328" href="hospital.html" title="VIRUTCHAM HOSPITAL">
                <area shape="rect" coords="1086,464,1196,539" href="park.html" title="AYYAPAKAM PARK">
                <area shape="rect" coords="240,194,429,259" href="dance.html" title="RACK ACADEMY OF DANCE">       
            </map>
        </center>
    </body>
</html>

home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Home</title>
    <style>
        body {
            background-color: rgb(142, 175, 215);
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 
                         'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
            padding: 20px;
            line-height: 1.6;
        }

        h2 {
            margin: 10px 0;
        }

        p {
            font-size: 16px;
            margin-top: 20px;
        }

        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>MY SWEET HOME</h2>
    <h2>PLACE OF COMFORT :</h2>
    <hr>
    <p>
        My home is a place of peace, warmth, and love. It's where family comes together and memories are made. 
        Whether it's enjoying meals, sharing laughter, or simply relaxing, my home provides comfort and security. 
        It's well-organized and welcoming, with cozy rooms and a friendly atmosphere. 
        More than just walls and a roof, it’s the heart of all our happiest moments.
    </p>
</body>
</html>

hall.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selvi Mahal Wedding Hall</title>
    <style>
        body {
            background-color: #5594c7;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 
                         'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
            padding: 20px;
            line-height: 1.6;
        }

        h2 {
            margin: 10px 0;
            color: #000000;
        }

        p {
            font-size: 16px;
            margin-top: 20px;
            color: #000000;
        }

        hr {
            border: 1px solid #ba55d3;
            width: 60%;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <h2>SELVI MAHAL </h2>
    <h2>PLACE OF CELEBRATION AND JOY :</h2>
    <hr>
    <p>
        Selvi Mahal Hall is the perfect destination for unforgettable celebrations. 
        With its elegant interiors, spacious halls, and excellent amenities, it offers a grand setting for weddings, receptions, and special events. 
        Known for its warm hospitality and beautiful ambiance, Selvi Mahal brings families and friends together to create cherished memories. 
        It's not just a venue—it's where love and tradition come alive.
    </p>
</body>
</html>

hospital.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virutcham Hospital</title>
    <style>
        body {
            background-color: #d6eaf8;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            padding: 20px;
            line-height: 1.6;
        }

        h2 {
            margin: 10px 0;
            color: #2c3e50;
        }

        p {
            font-size: 16px;
            margin-top: 20px;
            color: #34495e;
        }

        hr {
            border: 1px solid #2e86c1;
            width: 60%;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <h2>VIRUTCHAM HOSPITAL</h2>
    <h2>PLACE OF HEALING AND HOPE :</h2>
    <hr>
    <p>
        Virutcham Hospital is a trusted name in healthcare, offering compassionate and comprehensive medical services. 
        With a team of dedicated professionals and state-of-the-art facilities, it stands as a symbol of healing and care. 
        Patients are treated with dignity, and every effort is made to ensure their comfort and recovery. 
        More than a hospital, Virutcham is a place where hope is restored and lives are transformed.
    </p>
</body>
</html>

park.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayappakam Park</title>
    <style>
        body {
            background-color: #5f89d6;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 
                         'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
            padding: 20px;
            line-height: 1.6;
        }

        h2 {
            margin: 10px 0;
            color: #000000;
        }

        p {
            font-size: 16px;
            margin-top: 20px;
            color: #000000;
        }

        hr {
            border: 1px solid #000000;
            width: 60%;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <h2>AYAPPAKAM PARK</h2>
    <h2>PLACE OF NATURE AND RELAXATION :</h2>
    <hr>
    <p>
        Ayappakam Park is a green haven where people of all ages come to relax, play, and enjoy nature. 
        Surrounded by trees and open spaces, it provides a peaceful environment away from the city's rush. 
        With walking paths, play areas, and benches under the shade, it’s perfect for morning walks, family outings, or quiet reflection. 
        Ayappakam Park is a cherished community space where health, harmony, and happiness flourish.
    </p>
</body>
</html>

school.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RACK Academy of Dance</title>
    <style>
        body {
            background-color: #498fd5;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 
                         'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
            padding: 20px;
            line-height: 1.6;
        }

        h2 {
            margin: 10px 0;
            color: #000000;
        }

        p {
            font-size: 16px;
            margin-top: 20px;
            color: #000000;
        }

        hr {
            border: 1px solid #000000;
            width: 60%;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <h2>RACK ACADEMY OF DANCE</h2>
    <h2>PLACE OF RHYTHM AND EXPRESSION :</h2>
    <hr>
    <p>
        RACK Academy of Dance is a hub of talent, creativity, and movement. 
        With passionate instructors and a welcoming environment, it nurtures dancers of all ages and skill levels. 
        Whether it's classical, contemporary, hip-hop, or fusion, RACK inspires every student to express themselves through the power of dance. 
        It's more than just a dance school — it’s where passion meets performance and dreams take the stage.
    </p>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2025-05-02 161835.png>)
![alt text](<Screenshot 2025-05-02 162001.png>)
![alt text](<Screenshot 2025-05-02 201554.png>)
![alt text](<Screenshot 2025-05-02 202014.png>)
![alt text](<Screenshot 2025-05-02 202310.png>)
![alt text](<Screenshot 2025-05-02 203002.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
