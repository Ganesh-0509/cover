# Ex.06 Book Front Cover Page Design
## Date: 20/05/2025

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
    <title>Space Book</title>
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color: black;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10%;
            padding: 20px;
            font-family: 'Arial, sans-serif';
            background-image: url('space_background.png');
            background-size: cover;
        }

        .insight {
            color: azure;
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: rgb(255, 255, 255);
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            color: azure;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 180px;
        }

        .pub {
            color: azure;
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .ed {
            color: azure;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;
        }

        .subtitle {
            color: azure;
            font-family: unicorn;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="insight">
            SPACE JOURNAL
        </div>
        <div class="hrstyle">
            <hr style="color:blanchedalmond">
        </div>
        <div class="booktitle">
            <h1>JOURNEY TO THE STARS</h1>
        </div>
        <div class="subtitle">
            Guide for Young Explorers
        </div>
        <div class="subtitle">
            Featured Release 2025
        </div>

        <div class="id">
            <hr style="color:blanchedalmond">
        </div>
        <div class="author">
            <p><b>Ganesh Kumar T</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>LIMITED EDITION</b>
        </div>
    </div>
</body>

</html>


```


## OUTPUT:

![OUTPUT](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
