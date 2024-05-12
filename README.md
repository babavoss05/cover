# Ex.06 Book Front Cover Page Design
## Date:12-05-2024

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
### HTML
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Cloud Books</title>
        <title>Book Cover</title>
        <link rel="stylesheet" href="a.css">
    </head>
    <body>
    <div class="bookcover">
        <div class="head">
            <b>GOKUL CLOUD</b>
        </div>
        <div class="style">
            <hr style="color:rgb(209, 165, 165)">
        </div>
        <div class="title">
            <h1>CLOUD COMPUTING</h1>
        </div>
        <div class="subtitle">
            <b>INTRO TO CLOUD</b><br>
            <b>STRUCTURE OF CLOUD</b>
        </div>
        <div class="photo">
            <img src="image.jpg" width="90" height="100">
        </div>
        <div class="line">
            <hr style="color:rgba(144, 203, 219, 0.555)">
        </div>
        <div class="authorname">
            <p><b>GOKUL</b></p>
        </div>
        <div class="by">
            <h4>CLOUD INDUSTRY</h4>
        </div>
        <div class="about">
            <p>Cloud Computing: Concepts, Technology and Architecture is the result of years of research and analysis of the commercial cloud computing industry, cloud computing vendor platforms and further innovation .</p>
        </div>
    </div>
    </body>
</html>    
```

### CSS
```CSS
.bookcover{
    width: 400px;
    height: 600px;
    position: relative;
    top: 40px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family: ' Arial, sans-serif';
    background-image: url(cover.jpg);
    background-size: cover;
}
.head{
    color:rgb(0, 0, 0);

}
.style{
    width:90px;
}
.authorname{ 
    position: relative;
    color:rgb(0, 0, 0);
    top:190px;
    left:265px;
    font-size: medium;
}
.title{
    color:rgb(0, 0, 0);
    font-family: Roquen;
    font-size: larger;
    text-align: center;
    position: relative;
    top: 30px;
}
.line {
    width:400px;
    position: relative;
    top:270px;  
}
.by{
    color:rgb(0, 0, 0);
    font-size: medium;
    font-family: Verdana;
    position:relative;
    top:180px;
}
.subtitle{
    color:rgb(0, 0, 0);
    font-family: Verdana;
    font-size: large;
    position: relative;
    left:30px;
    top:40px;
}
.photo{
    position: relative;
    top: 180px;
    left: 260px;
    width: 90px;
    height: 80px;
    background-size:contain;
}
.about{
    color:rgb(0, 0, 0);
    position: relative;
    left:7px;
    top: 180px;
}
```


## OUTPUT:
![alt text](<Screenshot (335).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
