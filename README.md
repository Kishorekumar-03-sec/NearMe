# Ex04 Places Around Me
## Date: 29.04.2025
## Name: Kishorekumar S
## Reg no: 212224040162

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
<title> MY CITY</title>
</head>
<body>
<h1 align="'center">
<font color="299595"><b>Tiruvannamalai</b></font>
</h1>
<h3 align="centre">
<font color="76ccd3"><b> K DHANUSRI POOJA (24011393)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">

<area target="_parent" alt="home" title="home" href="tiru.html" coords="774,538,119" shape="circle">

<area target="_self" alt="dam" title="dam" href="dam.html" coords="275,642,111" shape="circle">

<area target="_self" alt="near" title="near" href="gingee.html" coords="1452,499,117" shape="circle">

<area target="_self" alt="jawadhuhills" title="jawadhuhills" href="hill.html" coords="339,133,216" shape="circle">

</map>
</center>
</body>
</html>

tiru.html

<html>
<head>
    <title>My City</title>
</head>
<body>
<h1 align="'center">
<font color="3d5891"><b>Tiruvannamalai</b></font>
</h1>
<h2 align="center">
<font color="7694d3"><b>Tiruvannamalai Karthigai Deepam </b></font>
</h2>
<hr size="3" color="3d5891">
<p align="justify">
<font face="Georgia" size="5">
    The Tiruvannamalai Karthigai Deepam is a revered festival celebrated at the Arunachaleswarar Temple 
in Tamil Nadu. In 2024, the festival spanned ten days, commencing on December 4 and culminating with the Maha Deepam on December 13. 
Karthigai Deepam commemorates the appearance of Lord Shiva as an infinite column of fire, symbolizing the triumph of light over darkness. The lighting of
the Maha Deepam atop Arunachala Hill at 6:00 PM on the final day represents this divine manifestation. 
    
</font>

    </p>
</body>
</html>

dam.html

<html>
<head>
    <title>My City</title>
</head>
<body>
<h1 align="'center">
<font color="3d5891"><b>Sathanur</b></font>
</h1>
<h2 align="center">
<font color="7694d3"><b>Sathanur Dam </b></font>
</h2>
<hr size="3" color="3d5891">
<p align="justify">
<font face="Georgia" size="5">
    
   
    Sathanur Dam, located approximately 30 km from Tiruvannamalai in Tamil Nadu, is a significant irrigation project and a
popular tourist destination. Constructed across the Thenpennai (Pennaiyar) River, the dam was completed in 1958 and stands as one of the major dams in the state .
</font>

    </p>
</body>
</html>

gingee.html

<html>
<head>
    <title>My City</title>
</head>
<body>
<h1 align="'center">
<font color="3d5891"><b>Gingee</b></font>
</h1>
<h2 align="center">
<font color="7694d3"><b>Gingee Fort</b></font>
</h2>
<hr size="3" color="3d5891">
<p align="justify">
<font face="Georgia" size="5">
    Gingee Fort, also known as Senji Fort, is a historic fortress located in the Villupuram district of Tamil Nadu, approximately 160 km from Chennai and 70 km from Puducherry. Often referred to as the "Troy of the East" by the British due to its formidable defenses, the fort is renowned for its strategic design and rich history.
    
</font>

    </p>
</body>
</html>

hill.html

<html>
<head>
    <title>My City</title>
</head>
<body>
<h1 align="'center">
<font color="3d5891"><b>Jawadhu</b></font>
</h1>
<h2 align="center">
<font color="7694d3"><b>Jawadhu Hills</b></font>
</h2>
<hr size="3" color="3d5891">
<p align="justify">
<font face="Georgia" size="5">
   The Jawadhu Hills (also spelled Javadhu or Jawadhi) are a serene extension of the Eastern Ghats, nestled between the Vellore and Tiruvannamalai districts in Tamil Nadu. Elevated between 1,000 to 1,350 meters above sea level, these hills offer a tranquil retreat from urban life, characterized by lush forests, tribal hamlets, and a cool climate.

    
    
</font>

    </p>
</body>
</html>

```


## OUTPUT

![map](https://github.com/user-attachments/assets/8fe8fa1f-8820-4fc7-87df-ec9506e11ad9)

![Screenshot 2025-04-25 104950](https://github.com/user-attachments/assets/f4cd4547-1a28-4233-8c7e-8e56bed62413)

![Screenshot 2025-04-25 105021](https://github.com/user-attachments/assets/1d7a6522-f81a-45ef-8036-f6685cb5b60b)

![Screenshot 2025-04-25 105006](https://github.com/user-attachments/assets/4915d944-65cc-40f3-9f69-270ae7566157)

![Screenshot 2025-04-25 104827](https://github.com/user-attachments/assets/da620ced-adf1-40f2-a683-a0a662ec1834)






## RESULT
The program for implementing image maps using HTML is executed successfully.
