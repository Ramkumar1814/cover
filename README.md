# Ex.05 Book Front Cover Page Design
## Date: 11/11/2024

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
## html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(230, 0, 255);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(background.jpg_auto=webp&s=b7d6873eed8c442bb685a083b3b4bfff6dd009ac);
            background-size: cover;
        }
        .insight{
            color: rgb(230, 0, 255);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color:rgb(230, 0, 255) ;
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 19px;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(230, 0, 255);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">EXPERT INSIGHT</div>
            <div class="hrstyle"><hr style="color: rgb(230, 0, 255);"></div>
            <div class="booktitle"><h1>MERN STACK WEB DEVELOPMENT</h1></div>
            <div class="subtitle">DESIGNING FRONTEND USING REACTJS</div>
            <div class="mypic"><img src="photome.jpeg" width="130" height="145" alt=""></div>
            <div class="id"><hr style="color: rgb(230, 0, 255);"></div>
            <div class="author"><p><b>RAMKUMAR S-212223220085</b></p></div>
            <div class="pub">OPEN >>></div>
            <div class="ed"><b>Special Edition</b></div>
        </div>
    </bodY>
</html>
```


## OUTPUT:
![Screenshot 2024-11-12 100518](https://github.com/user-attachments/assets/22d45a4b-c200-4386-a142-531ba51cc94f)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
