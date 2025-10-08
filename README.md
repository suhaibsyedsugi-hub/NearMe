# Ex04 Places Around Me
## Date: 8-10-25

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="temple" title="temple" href="1.html" coords="884,697,959,644" shape="rect">
    <area target="" alt="gingee" title="gingee" href="2.html" coords="1154,522,1347,600" shape="rect">
    <area target="" alt="muslims" title="muslims" href="3.html" coords="565,841,114" shape="circle">
    <area target="" alt="aruna" title="aruna" href="4.html" coords="1386,779,156" shape="circle">
    <area target="" alt="hall" title="hall" href="5.html" coords="499,398,718,482" shape="rect">
</map>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-10-08 201153.png>)
![alt text](<Screenshot 2025-10-08 201345.png>)
![alt text](<Screenshot 2025-10-08 201543.png>)
![alt text](<Screenshot 2025-10-08 201641.png>)









## RESULT
The program for implementing image maps using HTML is executed successfully.
