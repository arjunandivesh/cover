# Ex.05 Book Cover Page Design
## Date:15.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <head>
        <title>Cover Page</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body class="0">
        <div class="i3">
            <h1>STELLAR Explorations</h1>
            <br>
            <b>About the book</b>
            <hr color="red" size="4">
            <br>
            This book<font class="i2"> Stellar Explorations </font><font> presents a visually striking view of the universe, symbolizingx humanitys quest to understand the mysteries of space and science. The background features a vast cosmic scene filled with countless stars and a glowing nebula, representing the immense scale, beauty, and complexity of the cosmos. The deep shades of blue and black convey depth and infinity, while the warm luminous streak across the cover suggests energy, movement, and discovery.</font>
            <div>
                <br>
                <font class="i4">Stellar exploration is humanitys journey beyond the known, where curiosity becomes our compass among the stars.
Each discovery lights a path reminding us how small we are and how far we can reach.</font>
            </div>
            <br>
            <br>
             <hr color="pink" size="1" width="100px">
            <div class="i5"width="100px">
                <img src="my photo.jpg" style="height:120px;width: 120px;">
                <div class="i6">
                    <i>Divesh A</i>
                    <br>
                <P>
                    Stellar Explorations depicts the vast and mysterious universe. A glowing nebula and countless stars symbolize scientific discovery and cosmic wonder.The dark background represents the depth and infinity of space
                </P>
            </div>
            </div>
            <hr color="pink" size="2">
            <footer>
              <div class="footer">
        <div>SEC Publishers</div>
            <br>
            <DIV>Printed in India</div>
        <p align="right" >Price: $100</p>
         </div>

            </div>               
                <font>Printed in India</font>    
            </div>
        </div>
        </footer>
    </body>
</html>


styles.css

body{
    background-image: url("DG.png") ;
}
.color{
    color:black;
    background:radial-gradient(rgb(144, 139, 107),rgb(231, 213, 168),rgb(197, 183, 183));
    padding: 4px;
    border-radius: 5px 5px;
}
h1{
    padding-left: 6px;
    padding-top:22px;
    color:rgb(205, 66, 66)
}
font{
    font-size: 20;
    align-self: auto;
    color:black;
}
.i2{
    color:whitesmoke;
    padding:7px;
}
.i3{
    width: 720px;
    background:linear-gradient(rgb(177, 147, 184),rgb(123, 116, 124),rgb(171, 205, 224));
    margin: auto;
    border:solid 3px black;
    border-radius: 35px 35px;
    padding: 25px;
}
.i4{
    background:linear-gradient(45deg,rgb(72, 56, 119),rgb(146, 193, 196)); 
    padding: 17px;   
    margin:  auto;
    font-size: 18px;
    font-style: bold;
    display:flex;
    border-left: 7px solid;
    text-align: center;
}
.i5 {
    background:linear-gradient(rgb(225, 161, 207),rgb(193, 170, 222));    
    padding: 17px;
    width: 670px;
    margin: auto;
    border-radius: 17px;
    display: flex;
    gap: 17px;   
    border:dotted 5px rgb(241, 220, 220);                   
}
.i6 {
    font-size: 18;

}

.price{
    padding-left: 84%;
}
footer
{
    background-color: rgb(175, 149, 138);
    margin-top: 10px;
    font-weight: bold;
    border-left: 5px rgb(49, 107, 157) dotted;
    height: 55px;
    width: 660px;
    padding-bottom:7%;
    padding-top:1%;
    padding-left: 4%;
    padding-right: 4%;
    font-size: 80%;
  

}
```

## OUTPUT:
![alt text](<Screenshot (31).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
