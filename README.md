# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
clone the github repository into Theia IDE.

### Step 2:
Create a new Django project.

### Step 3:
Write the needed HTML code.

### Step 4:
Run the Django server and execute the HTML files.
## Code:
```
map.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Minjur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sachin Sagar S (22009268)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Govt Primary Hospital">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="Minjur Primary Health Center">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Minjur Government Library">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Minjur Town Panchayat Office">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Sai Ram Stores">
</map>
</center>
</body>
</html>

bus.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Minjur Town Panchayat Office</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Minjur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Minjur Town Panchayat Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Minjur is a Town Panchayat city in district of Thiruvallur, Tamil Nadu. The Minjur city is divided into 18 wards for which elections are held every 5 years. The Minjur Town Panchayat has population of 28,337 of which 14,168 are males while 14,169 are females as per report released by Census India 2011.
</b>
</font>
</p>
</body>
</html>

park.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Sai Ram Stores</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Minjur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sai Ram Stores</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Wholesale provison store .
</font>
</p>
</body>
</html>

rto.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Minjur Primary Health Center</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Minjur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Minjur Primary Health Center</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Government Primary Health Centre Hospital in Nandiambakkam, Tamil Nadu which is a public hospital for good medical treatment 
</b>
</font>
</p>
</body>
</html>

ghs.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt Primary Hospital</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Minjur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Govt Primary Hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Government primary Hospital is head Located in Minjur City
</font>
</p>
</body>
</html>

vk.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Minjur Government Library</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Minjur-City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Minjur Government Library</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Minjur Government Library
Address:77G5+XM6, Minjur, Tamil Nadu 601203
</font>
</p>
</body>
</html>
```

## Output:

![Output](./screenshots/out1.png)

![Output](./screenshots/out2.png)

![Output](./screenshots/out3.png)

![Output](./screenshots/out4.png)

![Output](./screenshots/out5.png)

![Output](./screenshots/out6.png)

## HTML Validator :
![HTML_Validator](./screenshots/vald.png)

## Result:
The program for implementing image map is executed successfully
