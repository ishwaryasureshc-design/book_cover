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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Journey of Perseverance</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      height: 100vh;
      width: 100vw;
      font-family: 'Segoe UI', sans-serif;
      background-image: url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1600&q=80');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
      position: relative;
    }

    /* Dark overlay for readability */
    body::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.45);
      z-index: 0;
    }

    .content {
      position: relative;
      z-index: 1;
      max-width: 80%;
    }

    h1 {
      font-size: 50px;
      color: #7CFC00;
      text-shadow: 2px 2px 5px #000;
      margin-bottom: 70px; /* 🌟 Increased space between title and quotes */
      text-transform: lowercase;
    }

    .quote {
      font-size: 22px;
      line-height: 1.6;
      color: #ffe97f;
      text-shadow: 1px 1px 3px #000;
      margin-bottom: 80px; /* Space before "Edited by" */
    }

    .author {
      font-size: 18px;
      color: #fcb3ff;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="content">
    <h1>journey of perseverance</h1>

    <div class="quote">
      keep growing, keep going<br>
      from struggle comes strength,<br>
      struggles shape strong souls.
    </div>

    <div class="author">
      Edition By<br>
      ishwaryasuresh (25015545)
    </div>
  </div>
</body>
</html>
```
# OUTPUT:

![alt text](<Screenshot 2025-10-05 221059.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
