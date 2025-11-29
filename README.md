# Ex03 Places Around Me
## Date: 29.11.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html
<html>       
    <head>
        <title> MAP LOCATION</title>
    </head>
    <body> 
        <h1 align="center">CHENGALPET CITY-MELMARUVATHUR</h1>         
        <h2 align="center">M.Dhanush &nbsp (25009955)</h2>
        <br>
        <img src="Screenshot 2025-11-28 130326.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="om shakthi temple" title="om shakthi temple" href="temple.html" coords="1100,244,1313,312" shape="rect">
    <area target="" alt="adhiparasakthi college of engineering" title="adhiparasakthi college of engineering" href="college.html" coords="948,133,135" shape="circle">
    <area target="" alt=" apoorva cafe" title=" apoorva cafe" href="cafe.html" coords="1367,135,1312,169" shape="rect">
    <area target="" alt="SMJ grand hotel and mahal" title="SMJ grand hotel and mahal" href="hotel.html" coords="1048,873,75" shape="circle">
    <area target="" alt="diraviyam gardens" title="diraviyam gardens" href="garden.html" coords="683,649,769,646,769,712,727,759,661,720" shape="poly">
</map>

    </body>
</html>

cafe.html
<html>       
    <head>
        <title>Location</title>
    </head>
    <body bgcolor="violet">          
        <h1 align="center">CHENGALPET CITY-MELMARUVATHUR</h1>
        <br>
        
        <h2 align="center">Apporva cafe</h2>
          <hr>
          Apoorva is a cherished culinary haven where tradition meets innovation.Known for its commitment to quality ingredients ,delightful flavours,an exceptional service.
         </body>
        
 </html>

 hotel.html
 <html>       
    <head>
        <title>Location</title>
    </head>
    <body bgcolor="indigo">          
        <h1 align="center">CHENGALPET CITY-MELMARUVATHUR</h1>
        <br>
        
        <h2 align="center">SMJ GRAND HOTEL AND MAHAL</h2>
          <hr>
          SMJ HUT - GARDEN is a great space ideal for training programmes, smaller conferences, corporate gatherings and office events. It provides a curated meeting place of up to 20 to 50 pax allowing you to have a seamless experience in a smaller environment. AC conference hall, SMJ Mahal can offer you a great pleasant and positive experience.
    </body>
</html>

garden.html
<html>       
    <head>
        <title>Location</title>
    </head>
    <body bgcolor="green">          
        <h1 align="center">CHENGALPET CITY-MELMARUVATHUR</h1>
        <br>
        
        <h2 align="center">diraviam garden</h2>
          <hr>
          Diraviam Garden is a residential area located in the town of Melmaruvathur, Tamil Nadu. It is primarily a layout offering plant sapplings for sale, near Acharapakkam and the GST road.
    </body>
</html> 

temple.html
<html>       
    <head>
        <title>Location</title>
    </head>
    <body bgcolor="red">          
        <h1 align="center">CHENGALPET CITY-MELMARUVATHUR</h1>
        <br>
        
        <h2 align="center">Adhiparasakthi temple</h2>
          <hr>
          The Adhiparasakthi Temple in Melmaruvathur is famous for being a significant pilgrimage site dedicated to the goddess Adhiparasakthi, its unique tradition of allowing women to perform pujas in the sanctum, and the presence of the Jeeva Samadhis of 21 siddhas (saints).
          
    
    </body>
</html>

college.html
<html>       
    <head>
        <title>Location</title>
    </head>
    <body bgcolor="orange">          
        <h1 align="center">CHENGALPET CITY-MELMARUVATHUR</h1>
        <br>
        
        <h2 align="center">ADHIPARASAKTHI COLLEGE OF ENGINEERING</h2>
          <hr>
          The Adhiparasakthi Engineering College, Melmaruvathur is one of the educational institutions functioning under the Adhiparasakthi Charitable, Medical, Educational and Cultural Trust. The institution is approved by the Government of Tamil Nadu and the All India Council for Technical Education and is affiliated to Anna University. All the departments of this college were accredited by National Board of Accreditation.
    </body>
</html>
```


## OUTPUT

![alt text](<Screenshot (19)-1.png>)

![alt text](<Screenshot (23)-1.png>)

![alt text](<Screenshot (22).png>)

![alt text](<Screenshot (20).png>)

![alt text](<Screenshot (24).png>)

![alt text](<Screenshot (21).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
