# Ex.06 Book Front Cover Page Design
# Date:5.10.25
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover - Web Development Essentials</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Poppins", sans-serif;
      background-color: #111;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .cover {
      width: 360px;
      height: 520px;
      background: linear-gradient(135deg, #6a11cb, #ff66b2);
      border: 4px solid #fff;
      box-shadow: 0 0 25px rgba(255, 255, 255, 0.4);
      position: relative;
      color: white;
      text-align: center;
      padding: 20px;
      box-sizing: border-box;
      border-radius: 10px;
    }

    .inner-border {
      border: 2px solid rgba(255, 255, 255, 0.6);
      height: 100%;
      padding: 20px;
      box-sizing: border-box;
      border-radius: 10px;
      background: linear-gradient(160deg, rgba(255,255,255,0.1), rgba(255,255,255,0.05));
    }

    .top-text {
      position: absolute;
      top: 25px;
      left: 30px;
      font-size: 13px;
      font-style: italic;
      color: #fff5f5;
    }

    h1 {
      font-size: 22px;
      font-weight: bold;
      margin-top: 70px;
      line-height: 1.5;
      letter-spacing: 1px;
      text-shadow: 1px 1px 3px #000;
    }

    .subtitle {
      font-size: 14px;
      margin-top: 15px;
      color: #ffe6f2;
      font-style: italic;
    }

    .edition {
      position: absolute;
      bottom: 70px;
      left: 25px;
      font-weight: bold;
      font-size: 13px;
      color: #fff;
    }

    .author {
      position: absolute;
      bottom: 35px;
      left: 25px;
      font-size: 14px;
      font-weight: bold;
    }

    .sec {
      position: absolute;
      bottom: 35px;
      right: 25px;
      font-size: 14px;
      font-weight: bold;
    }

    .author-img {
      position: absolute;
      bottom: 30px;
      right: 85px;
      width: 55px;
      height: 65px;
      border: 2px solid white;
      border-radius: 5px;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="inner-border">
      <div class="top-text">SEC Publications</div>
      <h1>WEB DEVELOPMENT<br>ESSENTIALS</h1>
      <div class="subtitle">
        Master HTML, CSS & JavaScript<br>
        The Complete Beginner’s Guide – 2025 Edition
      </div>

      <div class="edition">SPECIAL EDITION</div>
      <div class="author">Ishwarya</div>
      <div class="sec">SEC</div>
      <img src="" alt="Author Photo" class="author-img">
      <img src="Screenshot 2025-10-13 094725.png" alt="Author Photo" class="author-img">
    </div>
  </div>
</body>
</html>
     

```
# OUTPUT:
![alt text](<Screenshot 2025-10-13 094954.png>)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
