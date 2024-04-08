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
```
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<script>
    function coord(event) {
        let x=event.clientX;
        let y=event.clientY;
        document.getElementById("txt1").value=x;
        document.getElementById("txt2").value=y;
    }
</script>
<body>
    <img src="C:\Users\SYED ADIL BASHA\OneDrive\Pictures\Screenshots\Screenshot (173).png" width="1000px" usemap="#MapNew" onmousemove="coord(event)">
    <MAP name="MapNew">
        <AREA shape="RECT" coords="410,235,100,30" href="https://apolloartsandsciencecollegechennai.ac.in/default.aspx" Title="Apollo Arts and Science College" >
		<AREA shape="RECT" coords="928,77,340,190" href="https://saveethadental.com/" Title="saveetha dental college and hospital" >
		<AREA shape="RECT" coords="784,434,490,220" href="https://www.madhaengineeringcollege.com/" Title="Madha Engineering college" >
    </MAP> <br>
    X coord:<input type="text" name="" id="txt1"> <br>
    Y coord:<input type="text" name="" id="txt2"> 

</body>
</html>

```


## OUTPUT
![Screenshot (173)](https://github.com/SYEDADILBASHA1/NearMe/assets/134796157/c8ef0f2a-25bc-4652-8cbc-73dea59e17ef)



## RESULT
The program for implementing image maps using HTML is executed successfully.
