# Ex.06 Book Front Cover Page Design
## Name: GEETHU R
## Register No.: 212224040089
## Date:29-04-2025
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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Thing Beyond Forever - Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      background-color: #111;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 300px;
      height: 450px;
      background-image: url('template.png'); /* Ensure this file is in the same folder */
      background-size: cover;
      background-position: center;
      border-radius: 12px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      position: relative;
      overflow: hidden;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.3);
      width: 100%;
      height: 100%;
      position: absolute;
      top: 0;
      left: 0;
    }

    .content {
      z-index: 1;
      padding: 20px;
    }

    .quote {
      font-size: 0.9em;
      margin-bottom: 20px;
      line-height: 1.4;
    }

    .title {
      font-family: 'Brush Script MT', cursive;
      font-size: 2em;
      margin: 10px 0;
    }

    .author {
      font-size: 0.85em;
      margin-top: 30px;
      letter-spacing: 1px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="overlay"></div>
    <div class="content">
      <div class="quote">
        Did you happen to know?<br>
        Sky holds thousands of untold stories
      </div>
      <div class="title">Thing Beyond<br>Forever</div>
      <div class="author">A NOVEL BY GEETHU R</div>
    </div>
  </div>
</body>
</html>
~~~

## OUTPUT:
![book cover](https://github.com/user-attachments/assets/3d328f60-08d2-4c14-b9a0-af6a55c0d83e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
