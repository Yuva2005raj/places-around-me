# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

## Step 1:
Create a Django project abd app.

## Step 2:
create the html and css files based on your place in the image.

## Step 3:
Define new function in views file.

## Step 4:
Import views files and define the paths in urls file.

## Step 5:
Run the server
## Code:
## map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Chennai - Detroit of Asia</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Yuvaraj B (22008814)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="800,420,70" href="/static/html/park.html" title="Eco-Park">
<area shape="circle" coords="1000,420,100" href="/static/html/beach.html" title="Marina beach">
<area shape="circle" coords="1000,100,200" href="/static/html/memo.html" title="DR MGR Memorial">
<area shape="circle" coords="550,500,200" href="/static/html/temple.html" title="Murugan Temple">
<area shape="rectangle" coords="290,200,870,320" href="/static/html/Gm.html" title="Hi-Tech Museum">
</map>
</center>
</body>
</html>
```
## Output:

![out1](https://user-images.githubusercontent.com/118343998/215252606-566d903a-27d7-41c4-92c0-2364f529f672.png)




## Result:
The experiment was executed successfully.

