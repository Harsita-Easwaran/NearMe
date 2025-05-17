# Ex04 Places Around Me
## Date: 17/05/2025

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
'''
map.html

<!DOCTYPE html>
<html>
<head>
    <title>Places in Coimbatore</title>
    <style>
        area {
            cursor: pointer;
        }
    </style>
</head>
<body style="background-color: maroon;"> 
    <h1 align="center" style="color: white;">Coimbatore</h1>
    <h2 align="center" style="color: white;">Created By Harsita Easwaran (212224220036)</h2>

    <center>
        <img src="map.png" alt="Coimbatore Map" usemap="#coimbatore-map" width="900" style="height: auto;">

        <map name="coimbatore-map">
            <area shape="rect" coords="55,185,191,214" href="marudamalai.html" title="Marudhamalai Temple">
            <area shape="rect" coords="432,254,469,277" href="brookefields.html" title="Brookefields Mall">
            <area shape="rect" coords="435,298,472,322" href="voc.html" title="VOC Park and Zoo">
            <area shape="rect" coords="317,361,458,402" href="perur.html" title="Sri Perur Patteeswarar Temple">
            <area shape="rect" coords="612,225,753,266" href="airport.html" title="Coimbatore International Airport">
        </map>
    </center>
</body>
</html>

airport.html

<html>
    <head>
        <title>Coimbatore Airport</title>
    </head>
    <body bgcolor="LightSteelBlue">
        <h1 align="center">Coimbatore International Airport</h1>
        <h2 align="center">Peelamedu, Coimbatore</h2>
        <hr size="3" color="CornflowerBlue">
        <br><br>
        <p><h3>Coimbatore International Airport is the main airport serving Coimbatore city 
            and the surrounding region. It handles both domestic and international flights, 
            connecting the city to major destinations across India and abroad. The airport 
            features modern facilities, including passenger lounges, cargo services, and 
            convenient transportation options, making it an important gateway for travelers in 
            Tamil Nadu.</h3>
        </p>
    </body>
</html>

brookfields.html

<html>
    <head>
        <title>Brookefields Mall</title>
    </head>
    <body bgcolor="LightCyan">
        <h1 align="center">Brookefields Mall</h1>
        <h2 align="center">Brookebond Road, Coimbatore</h2>
        <hr size="3" color="SteelBlue">
        <br><br>
        <p><h3>Brookefields Mall in Coimbatore is a popular shopping and entertainment hub 
            featuring over 120 stores, a variety of restaurants, a six-screen PVR cinema, 
            and a children’s play area. Opened in 2009, it offers convenient facilities 
            like ample parking and wheelchair access, making it a favorite spot for both 
            locals and visitors.</h3>
        </p>
</html>

marudamalai.html

<html>
    <head>
        <title>Marudamalai Temple</title>
    </head>
    <body bgcolor="LavenderBlush">
        <h1 align="center">Marudamalai Murugan Temple</h1>
        <h2 align="center">Marudamalai Hills, Coimbatore</h2>
        <hr size="3" color="MediumOrchid">
        <br><br>
        <p><h3><b>Marudhamalai</b> is a famous hill temple dedicated to Lord Murugan, 
            located on the western outskirts of Coimbatore, Tamil Nadu. 
            Nestled amidst scenic hills and lush greenery, the Marudhamalai Temple 
            attracts devotees and tourists alike for its spiritual significance and 
            natural beauty. The temple is known for its peaceful environment, ancient architecture, 
            and vibrant festivals, especially during the Skanda Shasti festival. 
            It is a popular spot for both pilgrimage and nature lovers.</h3>
        </p>
</html>


perur.html

<html>
    <head>
        <title>Sri Perur Patteeswarar Temple</title>
    </head>
    <body bgcolor="Beige">
        <h1 align="center">Sri Perur Patteeswarar Temple</h1>
        <h2 align="center">Perur, Coimbatore</h2>
        <hr size="3" color="DarkGoldenrod">
        <br><br>
        <p><h3>Sri Perur Patteeswarar Temple is a historic Hindu temple dedicated to Lord Shiva, 
            located in Perur near Coimbatore. Known for its beautiful Dravidian architecture and 
            intricate carvings, the temple dates back over 2,000 years. It is an important cultural 
            and religious site, attracting devotees especially during festivals like Maha Shivaratri.</h3>
        </p>
    </body>
</html>


voc.html

<html>
    <head>
        <title>VOC Park and Zoo</title>
    </head>
    <body bgcolor="PaleGreen">
        <h1 align="center">VOC Park and Zoo</h1>
        <h2 align="center">Near Town Hall, Coimbatore</h2>
        <hr size="3" color="ForestGreen">
        <br><br>
        <p><h3>VOC Park and Zoo, located in Coimbatore, is a popular recreational spot featuring 
            a well-maintained zoo, children’s play area, and a beautiful park. Named after 
            freedom fighter V.O. Chidambaram Pillai, the park offers a peaceful environment for 
            families and nature lovers to relax and enjoy.</h3>
        </p>
    </body>
</html>

'''


## OUTPUT
![alt text](<Screenshot 2025-05-17 155139.png>)
![alt text](<Screenshot 2025-05-17 155149.png>)
![alt text](<Screenshot 2025-05-17 155203.png>)
![alt text](<Screenshot 2025-05-17 155217.png>)
![alt text](<Screenshot 2025-05-17 155229.png>)
![alt text](<Screenshot 2025-05-17 155240.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
