# Ex04 Places Around Me
# Date:
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
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>image mapping</title>
</head>
<body>
    <center>
    <img src="Screenshot 2024-10-24 144036.png" usemap="#image mapping">
    <map name="image mapping">
        <area target="blank" alt="map" title="CHENNAI" href="chennai.html" coords="270,93,368,85,388,155,272,135" shape="poly">
        <area target="blank" alt="map" title="TIRUPATHI" href="tirupathi.html" coords="130,4,214,8,205,50,128,49" shape="poly">
        <area target="blank" alt="map" title="VELLORE" href="vellore.html" coords="88,127,165,128,161,166,87,162" shape="poly">
        <area target="blank" alt="map" title="KANCHIPURAM" href="Kanchipuram.html" coords="180,137,288,142,285,185,182,176" shape="poly">
        <area target="blank" alt="map" title="TIRUVANAMALAI" href="tiruvanamalai.html" coords="76,237,249,240,249,286,83,282" shape="poly">
        <area target="blank" alt="map" title="PUDUCHERY" href="puduchery.html" coords="80,288,216,290,213,328,72,331" shape="poly">
    </center>
    
</body>
</html>
```
# OUTPUT
![Screenshot 2024-12-12 132849](https://github.com/user-attachments/assets/201e92b6-b04f-417d-a256-9ea4f200f283)


# RESULT
The program for implementing image maps using HTML is executed successfully.
