# Ex.06 Book Front Cover Page Design
## Date:30.11.2023

## AIM:
To design a book front cover page using HTML and CSS.

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
<!DOCTYPE html>
<html>

<head>
    <title>COMPUTER SCIENCE AND ENGINEERING</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(1234.JPG );
            background-size: cover;
        }
            
        
        .insight{
            color:aliceblue;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:white;
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:white;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:white;
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
        }
        .ed{
            color:white;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
        
        }
        .subtitle{
            color:darkorange;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
               SCOFT
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>COMPUTER SCIENCE AND ENGINEERING</h1></div>
            <div class="subtitle">
             Computer Science is the Operating System for all innovation.
            </div>
            <div class="subtitle">
                 
            </div>

            <div class="mypic">
                <img src="gaja.JPG" width="80" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>GAJALAKSHMI.V</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>

</html>

```


## OUTPUT:


![Screenshot 2023-11-30 111110](https://github.com/Gajalakshmivelmurugan/cover/assets/144871940/6aef6043-83db-4163-a4ad-a3b82ee062a0)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
