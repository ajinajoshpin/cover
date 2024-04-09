# Ex.06 Book Front Cover Page Design
## Date:09-04-2024

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
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(10, 10, 10);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('bookcover3.avif');
            background-size: cover;
        }

        .insight{
            color:rgb(13, 6, 6) ;

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: blue;
            display: inline;
            position: relative;
            color: rgb(42, 6, 245);
            top: 190px;

            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id{
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color: blue;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 85px;

        }
        .subtile{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
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
            <div class="EXPERT INSIGHT">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(10, 10, 10);">
            </div>
            <div class="booktitle">
                <h1>FULL STACK WEB DEVELOPMENT</h1>
            </div>
            <div class="subtitle">
              the comprehensive guide
            </div>
            <div class="mypic">
                <img src="ajinapic.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:rgb(10, 10, 10);">
            </div>
            <div class="author">
                <p><b>AJINA JOSHPIN</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:
![Screenshot 2024-04-09 140048](https://github.com/ajinajoshpin/cover/assets/148514578/22de4ca8-473c-42d6-91ba-7676f633cd9c)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
