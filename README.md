# Ex.08 Design of Interactive Image Gallery

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body {
            font-family:cursive;
            background-color:rgb(32, 28, 28);
            display:flex;
            justify-content: center;
            align-items: center;
            margin: 5;
            flex-direction: column;
            
        }
        .photo-container {
            text-align: center;
            color:bisque;
            font-size:medium;
        }

        .photo {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 50px; 
        }

        .photo-item {
            width: 400px; 
            height:600px;
                }
        footer {
            text-align: center;
            font-size: 30px;
            background-color:antiquewhite;
            margin-top: 250px; 
            color:darkred;
        }

    </style>
</head>
<body>
    <div class="photo-container">
        <h1 >GALLERY OF CRICKETERS</h1>
        <div class="photo">
            <img src="dhoni.jpg" alt="Image 1" class="photo-item" >
            <img src="rishab.jpg" alt="Image 2" class="photo-item">
            <img src="14.avif" alt="Image 3" class="photo-item">
            <img src="hardik.jpg" alt="Image 4" class="photo-item">
            <img src="virat.jpg" alt="Image 5" class="photo-item">
            
        </div>
        <footer>
            Designed and developed by Tharshini&copy 2025
        </footer>
    </div>
    
</body>
</html>

  
```

### OUTPUT
![alt text](image.png)





## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
