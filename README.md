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
meena.html
<html>
<head>
    <title>Book Cover</title>
    <link href="devan.css" rel="stylesheet">
</head>

<body>

<div class="box">
    <h2>About the Book</h2>
    <hr style="height:2px;border-width:0;color:rgb(15, 15, 15);background-color:rgb(8, 8, 8)">

    <p>
        This book,<b style="background-color: yellow;">"Introduction to Full Stack Development"</b> , is designed to provide a foundational understanding of the concepts, tools, and technologies involved in full stack application development. It introduces readers to the core components of modern web development, including HTML, CSS, and JavaScript for front-end design; server-side programming concepts; database management; APIs; and deployment fundamentals. The book emphasizes practical learning, helping readers understand not only what each technology does, but how and why it is used in real-world applications.
    </p>
    <br>
    <br>

    <div class="quote">
        <br>
        "Understanding Every Layer of Modern Web Development"
        <br>
        <br>
    </div>

    <br>
    <br>
    

    
    <div class="author">
        <img src="coverimage.jpeg" alt="Author Photo">

        <p>
            <b>LAKSHITA RAI.V(25005431)</b><br>
            
            As a student of Saveetha Engineering College and studying B.TECH IT department.
            

        </p>
    </div>

    <div class="footer">
        <table>
        <tr>
            <td style="color: yellow;">SEC Publishers</td>
            <td style="color: white; padding-left: 200;">Price: <b style="color: yellow;">$1000</b></td>
        </tr>
        <tr>
            <td style="color: white;">Published in India</td>
        </tr>
        </table>
    </div>

</div>

</body>
</html>
```
```
devan.css
  body {
            font-size: Arial;
            background:linear-gradient;
        }
        .box {
            height: 700px;
            width: 500px;
            background-image:url(coverback.jpeg);
            background-size: cover;
            color:rgb(14, 12, 12);
            padding: 20px;
            margin: 30px auto;
            border: 2px solid blue;
            border-radius: 10px;
        }
        .quote {
            background: rgb(198, 214, 214);
            padding: 10px;
            border-left: 4px solid blue;
            margin: 20px 0;
            font-style: italic;
            text-align: center;
            border-end-end-radius: 10px;
        }
        .author {
            display: flex;
            gap: 15px;
            background:rgb(15, 40, 231);
            padding: 10px;
            border-start-end-radius: 5px;
        }
        .author b{
            color:rgb(242, 245, 245);
        }
        .author img {
            width: 80px;
            height: 90px;
            border-radius: 5px;
        }
        .footer {
            background: rgb(44, 50, 121);
            color: rgb(247, 227, 11);
            display: flex;
            padding: 10;
            justify-content: space-between;
            margin-top: 100px;
            border-end-end-radius: 5px;
        }
```

 ## OUTPUT:
![alt text](<sona/coverapp/static/Screenshot 2025-12-16 115701.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
