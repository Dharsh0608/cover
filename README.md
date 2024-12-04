# Ex.06 Book Front Cover Page Design
## Date:3-12-2024

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }


    .book-cover {
      width: 300px;
      height: 450px;
      background: url('cover.jpg') no-repeat center;
      background-size: cover;
      color: white;
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 20px;
      position: relative;
    }
.expert
{
    position:absolute;
    top:200px;
    left:600px;
    color:white;
}
    .book-title {
      font-size: 25px;
      font-weight: bold;
      text-align: left;
      margin-bottom: 50px;
      padding: 0 40px;
    }
    .book-title p{
        font-size: 15px;
        font-family: 'Courier New', Courier, monospace;
    }

    .book-sub{
      font-size: 12px;
      position: absolute;
      bottom: 800px;
      text-align: left;
      margin-bottom:40px;
      padding: 0 60px;
    }

    .book-image {
      height: 100px;
      margin: 20px auto;
      padding-left: 190px;
      border: 2px solid rgba(22, 22, 1, 0.944);
      border-radius: 8px;
      overflow: hidden;
      
    }

    .book-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .tagline {
      font-size: 20px;
      font-style: italic;
      text-align: left;
      margin: 35px 0;
      padding: 0 35px;
    }
    .right
    {
        color: white;
        position: absolute;
        left:250px;
        bottom:30px;
    }
    .left
    {
        color: white;
        position: absolute;
        right: 180px;
        bottom:30px;
    }
    
  </style>
</head>
<body>
    <div class="expert">EXPERT INSIGHT</div>
  <div class="book-cover">
    <div class="book-title">The Fundametals of Web Development
        <p>"Coming over the element that scares you everyday!"</p>
    </div>
    

    <div class="book-image">
      <img src="DHARSHANA.jpg" alt="author">
    </div>
    <div class="tagline">Eighth Edition</div>
      <div class="left">Dharshana A S</div>
      <div class="right">SEC</div>
    </div>
  </div>
</body>
</html>
```


## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
