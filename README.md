# Ex.06 Book Front Cover Page Design
## Date:19.12.25

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
  <meta charset="UTF-8">
  <title>Book Cover - SANJAY S</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Segoe UI', sans-serif;
    }

    .cover {
      width: 400px;
      height: 600px;
       background-image: url(msdhoni.jpg);
  background-size: cover;          /* makes the image cover the whole area */
  background-repeat: no-repeat;    /* avoids tiling */
  background-position: center;     /* centers the image */

      box-shadow: 0 0 20px rgba(0,0,0,0.5);
      padding: 30px;
      box-sizing: border-box;
      text-align: center;
      color: #4105f6; /* text set to white for contrast */
    }

    .title-box {
      border: 2px solid rgba(12, 12, 12, 0.9);
      padding: 20px;
      margin-bottom: 20px;
      background: rgba(255,255,255,0.03);
    }

    .title-box h1 {
      font-size: 24px;
      line-height: 1.4;
      margin: 0;
      color: inherit;
    }

    .subtitle {
      font-size: 16px;
      font-style: italic;
      margin-top: 10px;
      color: #000b0e;
    }

    .photo-box {
      margin: 20px 0;
    }

    .author-photo {
      width: 150px;
      height: 150px;
      border-radius: 5px;
      object-fit: cover;
      border: 2px solid rgba(16, 15, 15, 0.9);
    }

    .author-name {
      font-size: 18px;
      font-weight: bold;
      margin-top: 10px;
      color: inherit;
    }

    .divider {
      border: none;
      height: 2px;
      background-color: rgba(3, 3, 3, 0.3);
      margin: 20px 0;
    }

    .course-info {
      font-size: 14px;
      margin-top: 10px;
      color: #024060;
      line-height: 1.4;
    }

    .edition {
      font-size: 12px;
      margin-top: 10px;
      color: #02203a;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="title-box">
      <h1>M S DHONI</h1>
      <p class="subtitle"> M S DHONI BIOGRAPHY</p>
    </div>
    <div class="photo-box">
      <img src="sanj.jpg" alt="SANJAY S" class="author-photo">
    </div>
    <p class="author-name">by SANJAY S </p>
    <hr class="divider">
    <p class="course-info">Saveetha Engineering College<br>19AI414 - Web Application Development</p>
    <p class="edition">DECEMBER 2025 Edition</p>
  </div>
</body>
</html>
```

## OUTPUT:
<img width="498" height="744" alt="Screenshot 2025-12-19 112216" src="https://github.com/user-attachments/assets/77c712dd-e572-4c28-9869-c1d62e92d31f" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
