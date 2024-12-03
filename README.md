# Ex04 Places Around Me
## Date: 20.11.2024

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

<html>
    <head>
        <title>My Place</title>
    </head>
    <body>
    <h1 align="center">
        <font color="red"><b>Kolathur</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>S SIDDHARTH (24002384)</b></font>
    </h3>
    <center>
        <img src="map.png.png" usemap="#MYCITY" height="610" width="1450">
        <map name="MyPlace"
            <area shape="rect" coords="700,250,900,900" href="home.html" title="MY HOME TOWN">
            <area shape="circle" coords="700,250,900,900" href="gym.html" title="MY GYM">
            <area shape="circle" coords="700,250,900,900" href="reliance.html" title="MY stor">
            <area shape="circle" coords="700,250,900,900" href="market.html" title="MY market">

        </map>
    </center>

    </body>
</html>


## OUTPUT

![alt text](map.png.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
