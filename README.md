# Ex04 Places Around Me
## Date: 

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

Map.html
```
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Cuddalore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Lidison sham M  (212224040171)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="rect" coords="970,390,1020,440" href="beach.html" title="Silver Beach">
<area shape="circle" coords="470,190,30" href="puducherry.html" title="Puducherry">
<area shape="rect" coords="400,150,250,100" href="Manikoondu.html" title="Manikoondu">
<area shape="circle" coords="970,390,102" href="Devanampattinam.html" title="Devanampattinam">
<area shape="rect" coords="600,150,102,100" href="chavadi.html" title="Chavadi">
</map>
</center>
</body>
</html>
```
home.html
<head>
  <title>Cuddalore - Coastal City of Tamil Nadu</title>
</head>
<body>

  <h1>Welcome to Cuddalore</h1>
  <p>A peaceful coastal town in Tamil Nadu, India.</p>
  <h2>About Cuddalore</h2>
  <p>
    Cuddalore is a historic city located on the Coromandel Coast of the Bay of Bengal.
    Known for its serene beaches, temples, and colonial heritage, Cuddalore offers a unique mix of nature and culture.
  </p>

  <h2>Popular Attractions</h2>
  <ul>
    <li>Silver Beach</li>
    <li>Padaleeswarar Temple</li>
    <li>Fort St. David</li>
    <li>Devanampattinam</li>
    <li>Pichavaram Mangrove Forest</li>
  </ul>

  <hr>
  <p>&copy; 2025 Explore Cuddalore</p>

</body>
</html>
<!DOCTYPE html>
<html>
<head><title>Silver Beach</title></head>
<body>
  <h1>Silver Beach, Cuddalore</h1>
  <p>One of the longest beaches in Asia, perfect for relaxation and beach activities.</p>
</body>
</html>
<!DOCTYPE html>
<html>
<head><title>Puducherry</title></head>
<body>
  <h1>Puducherry</h1>
  <p>Known for its French colonial heritage, serene beaches, and Auroville township.</p>
</body>
</html>
<!DOCTYPE html>
<html>
<head><title>Devanampattinam</title></head>
<body>
  <h1>Devanampattinam</h1>
  <p>A beachside area with a strong fishing community and calm surroundings.</p>
</body>
</html>
<!DOCTYPE html>
<html>
<head><title>Manikoondu</title></head>
<body>
  <h1>Manikoondu</h1>
  <p>A key junction in Cuddalore with hotels and transport connectivity.</p>
</body>
</html>
<!DOCTYPE html>
<html>
<head><title>Chavadi</title></head>
<body>
  <h1>Chavadi</h1>
  <p>A peaceful locality near Puducherry, popular for commuters and residential stay.</p>
</body>
</html>

## OUTPUT
![image](https://github.com/user-attachments/assets/d84e059a-deba-4e4f-9fbb-48de051e642a)








## RESULT
The program for implementing image maps using HTML is executed successfully.
