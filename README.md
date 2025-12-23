# Ex.05 Book Cover Page Design
## Date:23-12-2025

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
cover.html

<html>
    <head>
        <title>My book</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="box1">
            <h1>The Last Light of Tomorrow</h1>
            <hr>
            <p style="font-size: 20px;margin-left: 80px;color: dimgray;"><u>The Last Light of Tomorrow</u> In a world where hope is slowly fading, a brave teenager discovers a secret that could change the future forever. As friendships are tested and tough choices must be made, the story explores courage, loyalty, and the power of believing in yourself—even when everything seems lost.

From learning the basics of hardware and software to exploring the internet, apps, and everyday digital tools, each chapter is designed to make technology feel easy, useful, and fun.</p>
        <div class="box2">
            <li>
                <ul>The future isnt coming  its already here. Step in.</ul>
                <ul>Learn today. lead tomorrow.</ul>
            </li>
        </div>

        <div class="box3">
            <img src="1.png">
            <div class="info">
                <h3>PARVESHWARAN R</h3>
                <p style="margin-top: 5px;margin-left: 20px;">PARVESHWARAN R is a student in saveetha engineering college currently doing UG program in Computer Science Engineering(CSE).He completed his higher studies in bio-maths stream.</p>
            </div>
        </div>
        <div class="box4">
            <h2>PARAS PUBLISHER</h2>
            <h4>&copy; Unauthorized copying or reproduction of this material is strictly prohibited.</h4>
            <div class="amount">
                <h5>Price: &#8377 1000</h5></div>
            </div>
        </div>
    </body>
</html>

style.css

.box1
{
    height: 100%;
    width: 45%;
    border: solid 3px;
    margin-left: 365px;
    padding-bottom: 100px;
    margin: auto;
    border-radius: 15px;
    background:linear-gradient(red,blue);
}
.box2
{
     height: 115px;
    width: 500px;
    margin-left: 80px;
    border-left: solid 3px;
    background-color: gray;
    display: flex;
}
.box3
{
    height: 130px;
    width: 500px;
    margin-left: 80px;
    margin-top: 25px;
    border: solid 2px;color: black;
    background-color: white;
    display: flex;
    align-items: flex-start;
}
.info
{
    display: flex;
    flex-direction: column;
}
h1{
    margin-left: 80px;
    margin-top: 65px;
}
img{
    height: 130px;
    width: 120px;
    
}
h3{
    margin-left: 15px;
    margin-left: 20px;
    margin-bottom: 5px;
}
h4
{
    margin-left: 15px;
}
.box4
{
    height: 170px;
    width: 500px;
    margin-left: 80px;
    margin-top: 15px;
    background-color:peachpuff;
    border: solid 3px;
    border-radius: 5px;
    display: flexbox;
}
.amount
{
    display: flex;
    flex-direction: row-reverse;
    padding-bottom: 15px;
    padding-right: 15px;
}
h5
{
    font-size: 15px;
    margin-bottom: 15px;
}
hr{
    color: whitesmoke;
    border: solid 3px;
    margin-left: 80px;
}
h2
{
    margin-left: 15px;
}
```

## OUTPUT:
![alt text](<Screenshot (40).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
