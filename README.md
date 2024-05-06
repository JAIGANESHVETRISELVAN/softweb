# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
people.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px salmon solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: aqua;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            /* bottom: 0; */
            right: 0;
            left: 0;
            border: 10px rgb(20, 166, 224) solid;
            background-color: yellow;
        }
        .navbar{
            background-color: rgb(41, 173, 36);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            margin-bottom: 80px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:blue ;
        }
        .content{
            margin: 10px;
            padding: 10px;
            background-color:rgb(246, 246, 248) ;
        }
        .content h1{
            text-align: center;
        }
        .content h4{
            text-align: center;
        }
       img{
            width: 100px;
            height: 100px;
        }
        #people{
            display: flex;
            /* justify-content: center; */
            align-items: center;
            flex-direction: column;
        }
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">

            
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="people.html">PEOPLE</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
        PEOPLE
    </div>
    <div class="content" style="border: 5px red solid;">
        <h1>BOARD MEMBERS</h1>
        <div id="people">
        <h4>Chairman</h4>
        <scan><img src="jai.jpg" alt="chairman"></scan>
        <scan>JAIGANESH V</scan>
        <h4>HEAD EXECUTIVES</h4>
        <scan><img src="rohit.jpeg" alt="cairman"></scan>
        <scan>ROHIT SHARMA</scan>
        <scan><img src="KOHLI.jpeg" alt="cairman"></scan>
        <scan>VIRAT KOHLI</scan>
    </div>
    </div>
    </div>
</body>
</html>
```
```
product.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px salmon solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: aqua;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            /* bottom: 0; */
            right: 0;
            left: 0;
            border: 10px rgb(20, 166, 224) solid;
            background-color: yellow;
        }
        .navbar{
            background-color: rgb(41, 173, 36);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            margin-bottom: 80px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:blue ;
        }
        .content{
            margin: 10px;
            padding: 10px;
            background-color:rgb(246, 246, 248) ;
        }
        .content h1{
            text-align: center;
        }
        .content h2{
            text-align: center;
            color: rgb(44, 188, 130);
        }
        .grid-view{
            display: flex;
            /* justify-content: center; */
            align-items: center;
            flex-direction: column;
        }
        .cl{
            border: 2px saddlebrown solid ;
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">

            
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="people.html">PEOPLE</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
PRODUCT
    </div>
    <div class="content">
        
        <h2>These are the programming languages that are available now</h2>
        <div class="grid-view">
           
                <scan class="cl"><img src="cimage.png" ></scan>
                <scan>C++</scan>
         
           
                <scan class="cl"><img src="reactimage.png" alt="chairman"></scan>
                <scan>React</scan>
            
                <scan class="cl"><img src="kotlinimage.png" alt="chairman"></scan>
                <scan>Kotlin</scan>
            
                <scan class="cl"><img src="pythonimage.jpeg" alt="chairman"></scan>
                <scan>Python</scan>
            
        </div>
        
    </div>
    </div>
</body>
</html>
```
```
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px salmon solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: aqua;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            bottom: 0;
            right: 0;
            left: 0;
            border: 10px rgb(20, 166, 224) solid;
            background-color: yellow;
        }
        .navbar{
            background-color: rgb(41, 173, 36);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:blue ;
        }
        .content{
            margin: 10px;
            padding: 10px;
            background-color:rgb(246, 246, 248) ;
            border: 5px salmon solid;

        }
        .content h1{
            text-align: center;
        }
        .content h4{
            text-align: center;
        }
        .contact-info{
            padding: 20px;
        }
        .contact-info div{
            padding: 10px;
        }
        .contact-info div b{
            padding: 10px;
        }
        
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">
  
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="people.html">PEOPLE</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
    CONTACT US
    </div>
    <div class="content">
        <h1>HERE ARE THE DETAILS ABOUT US</h1>
        <h4>DO CONTACT US FOR ANY NEED</h4>
        <div ><b> CONTACT INFORMATION:</b></div>
        <div class="contact-info">
        <div ><b>Address:</b>2.233/2 Madha kovil street,Thiruvarur</div>
        <div ><b>Landline:</b>140 8904 1353</div>
        <div><b>Phone:</b>9360246488</div>
        <div><b>Email:</b>jaiganesh9604@gmail.com</div>
        
        

        

    </div>
    </div>
    </div>
</body>
</html>
```
```
softweb.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px salmon solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: aqua;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            bottom: 0;
            right: 0;
            left: 0;
            border: 10px rgb(20, 166, 224) solid;
            background-color: yellow;
        }
        .navbar{
            background-color: rgb(41, 173, 36);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:blue ;
        }
        .content{
            margin: 10px;
            padding: 10px;
            background-color:rgb(246, 246, 248) ;
        }
        .content h1{
            text-align: center;
        }
        .content h4{
            text-align: center;
        }
        img{
            width: 400px;
            height: 200px;
        }
        .center{
            display: block;
            margin-left: auto;
            margin-right: auto;
            border: 5px green solid;

        }
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">

            
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="people.html">PEOPLE</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
        JAIGANESH SOFTWARE DEVELOPING CENTER
    </div>
    <div class="content">
        <h1>MAKING YOUR FUTURE BRIGHT BY SKILLS</h1>
        <h4>OFFICIAL WEBSITE</h4>
        <div>Jaiganesh Software Developing Center is a dynamic hub for software innovation, fostering collaboration and continuous learning. </div>
        <div>With a diverse team of talented individuals, the center excels in crafting elegant solutions to complex challenges. From intuitive user interfaces to scalable systems, Jaiganesh Software Developing Center is dedicated to pushing boundaries and shaping the future of technology with creativity and innovation.</div>
        <div ><img src="dev.png" class="center"></div>
    </div>
    </div>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-05-06 131926.png>)
![alt text](<Screenshot 2024-05-06 131945.png>)
![alt text](<Screenshot 2024-05-06 132003.png>)
![alt text](<Screenshot 2024-05-06 132110.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
