# Ex04 Places Around Me
## Date: 09.12.2025

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="magenta"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>RAGAVAN</b></font>
</h3>
<center>
<map name="MyCity">
<img src="mymap.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="Avadi" title="avadi" href="beach.html" coords="16,66,180,148" shape="rect">
    <area target="_self" alt="ennor" title="ennor" href="college.html" coords="493,232,704,294" shape="rect">
    <area target="_self" alt="Sriperumbudur" title="Sriperumbudur" href="D:\web\EX4\Image_map\kishore\mapapp\static\forest.html" coords="546,398,617,441" shape="rect">
    <area target="_self" alt="Thoraipakkam" title="" href="mytown.html" coords="995,116,1098,165" shape="rect">
    <area target="_self" alt="Perungalathur" title="Perungalathur" href="temple.html" coords="1079,13,1237,101" shape="rect">
</map>
</map>
</center>
</body>
</html>

beach.html

<html>
<head>
<title>AVADI</title>
</head>
<body bgcolor="silver">
<h3 align="center">
<font color="black"><b>AVADI</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Avadi is a city comes under the Chennai metropolitan area, Its the headquarters of Avadi City Police, Avadi City Corporation and Avadi Taluk located within the Chennai district of Tamil Nadu, India.
</body>
</html>

college.html

<html>
<head>
<title>ENNORE</title>
</head>
<body bgcolor="aqua">
<h3 align="center">
<font color="black"><b>ENNOR</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Ennor (or Ennore) refers to several things: a significant coastal neighborhood in Chennai, India, known for its port and power station; a major Indian company, Ennor Muds & Chemicals, serving the oil & gas sector; a musical group called Ennor Music; and in literature, an alternative name for Middle-earth in J.R.R. Tolkien's works, notes Tolkien Gateway.
</body>
</html>

forest.html

<html>
<head>
<title>SRIPERUMBUDUR</title>
</head>
<body bgcolor="silver">
<h3 align="center">
<font color="black"><b>SRIPERUMBUDUR</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Sriperumbudur, also known as Thiruperumbudur, is a Municipality and the headquarters of Sriperumbudur taluk located in Kanchipuram district of the Indian state of Tamil Nadu. Located 40 kilometers southwest of the capital city of Chennai on the National Highway 4, it falls under the Chennai Metropolitan Area.
</body>
</html>

mytown.html

<html>
<head>
<title>THORAIPAKKAM</title>
</head>
<body bgcolor="aqua">
<h3 align="center">
<font color="black"><b>THORAIPAKKAM</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Thoraipakkam is a rapidly developing residential and commercial area located along the Old Mahabalipuram Road (OMR) in Chennai, India. Known for its proximity to IT hubs and educational institutions, Thoraipakkam has become a preferred location for professionals working in the technology sector. The area boasts modern amenities, shopping centers, and a variety of dining options, making it a vibrant community for residents and visitors alike.
</body>
</html>


temple.html

<html>
<head>
<title>PERUNGALATHUR</title>
</head>
<body bgcolor="skyblue">
<h3 align="center">
<font color="black"><b>PERUNGALATHUR</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Perungalathur is a town located in the southern part of Chennai, Tamil Nadu, India. It is known for its residential neighborhoods, educational institutions, and proximity to various IT parks and commercial hubs. The town has seen significant development in recent years, making it a popular choice for families and professionals seeking a suburban lifestyle while still being close to the city's amenities.
</html>
</body>
</html>
~~~


## OUTPUT
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/9e3fbede-b8fa-4b23-83b5-85afd6ec63ca" />
<img width="1920" height="1080" alt="Screenshot 2025-12-09 222043" src="https://github.com/user-attachments/assets/6f6106e9-f66e-4dcf-9228-757619b96d1b" />
<img width="1920" height="1080" alt="Screenshot 2025-12-09 222429" src="https://github.com/user-attachments/assets/c6e5f951-e250-444c-a99a-1254553d1c16" />
<img width="1920" height="1080" alt="Screenshot 2025-12-09 222703" src="https://github.com/user-attachments/assets/13696f30-48c5-43e9-b850-667f37c511d0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b9f35385-4229-472f-81c6-0bac8ff56e55" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5c6b6aa-b14b-4749-ade9-273b0fd0a3a7" />











## RESULT
The program for implementing image maps using HTML is executed successfully.
