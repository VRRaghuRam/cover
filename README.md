# Ex.06 Book Front Cover Page Design
## Date:03/12/2024

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
cover.html

<html>

<head>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

    <style>
        .space {
            width: 35%;
            height: 100%;
        }

        .first{
            position: absolute;
            top:23px;
            left: 650px;
            color: white;
            font-weight: 900;
            font-size: 32px;
            font-style: none;
            line-height: 1.2;
            margin-bottom: 5px;
        }

        .second{
            position: absolute;
            top: 60px;
            left: 400px;
            color: white;
            font-style: italic;
            font-family: 'Montserrat', sans-serif;
            font-weight: 900;
            font-size: 20px;
            line-height: 1.2;
            margin-bottom: 5px;
        }

        .about{
            position: absolute;
            top: 85px;
            left: 525px;
            right: 540px;
            color: white;
            font-style: oblique;
            font-variant: normal;
            font-weight: lighter;
            font-family: none;
            font-size: 20px;
        }

        .edition {
            position: absolute;
            bottom: 80px;
            left: 520px;
            right: 600px;
            color:rgb(213, 47, 47);
            font-style: oblique;
            font-variant: normal;
            font-family: monospace;
            font-size: 20px;
        }
        .author{
            position: absolute;
            bottom: 30px;
            left: 520px;
            right: 600px;
            color: rgb(213, 47, 47);
            font-style: oblique;
            font-variant: normal;
            font-family: monospace;
            font-size: 20px;
        }
        .pub{
            position: absolute;
            bottom: 40px;
            right: 525px;
            left: 940px;
            color: rgb(213, 47, 47);
            font-style: oblique;
            font-variant: normal;
            font-family:monospace;
            font-size: 20px;
        }
        .raghu
        {
            position: absolute;
            bottom: 110px;
            right: 500px;
            left: 915px;
            width: 6%;
        }

        .pub2{
            position: absolute;
            bottom: 20px;
            right: 525px;
            left: 890px;
            color: rgb(213, 47, 47);
            font-style: oblique;
            font-variant: normal;
            font-family:monospace;
            font-size: 20px;
        }
    </style>
    </style>

</head>

<body>
    <div class="cover">
        <center>
            <img src="space.png" class="space">
        </center>
        <center>
            <img src="RAGHU.JPG" class="Raghu">
        </center>
        <h1 class="first">COSMOLOGY</h1>
        <h3 class="second"></h3>
        <p class="about">
            Cosmology is a branch of metaphysics that deals with the nature of the universe, a theory or doctrine
            describing the natural order of the universe.
        </p>
        <p class="edition">
            THIRD Edition
        </p>
        <p class="author">
            Raghu Ram
        </p>
        <p class="pub">
            SEC 
        </p>
        <p class="pub2">
            Publications
        </p>
    </div>
    </div>

</body>

</html>

```


## OUTPUT:

![alt text](<Screenshot (29).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
