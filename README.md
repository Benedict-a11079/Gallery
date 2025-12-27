# Ex.08 Design of Interactive Image Gallery
# Date:13.12.2025
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Interactive Image Gallery</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #0f172a;
            color: white;
            text-align: center;
            margin: 0;
            padding: 20px;
        }

        h1 {
            margin-bottom: 20px;
        }

        /* Main Image */
        #mainImage {
            width: 60%;
            max-height: 400px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(255,255,255,0.3);
            margin-bottom: 20px;
            transition: 0.3s;
        }

        /* Thumbnail Container */
        .gallery {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }

        .gallery img {
            width: 120px;
            height: 80px;
            cursor: pointer;
            border-radius: 8px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 10px white;
        }
    </style>
</head>

<body>

    <h1>Interactive Image Gallery</h1>

    <!-- Main Display Image -->
    <img id="mainImage" src="img1.jpg" alt="Main Image">

    <!-- Thumbnails -->
    <div class="gallery">
        <img src="c:\Users\acer\OneDrive\Desktop\mapi\download (1).jpg" onclick="changeImage(this.src)">
        <img src="c:\Users\acer\OneDrive\Desktop\mapi\download (2).jpg" onclick="changeImage(this.src)">
        <img src="c:\Users\acer\OneDrive\Desktop\mapi\download.jpg" onclick="changeImage(this.src)">
        <img src="c:\Users\acer\OneDrive\Desktop\mapi\download.png" onclick="changeImage(this.src)">
        <img src="c:\Users\acer\OneDrive\Desktop\mapi\images.jpg" onclick="changeImage(this.src)">
    </div>

    <script>
        function changeImage(imageSrc) {
            document.getElementById("mainImage").src = imageSrc;
        }
    </script>

</body>
</html>

# OUTPUT:
<img width="1886" height="876" alt="Screenshot 2025-12-27 223958" src="https://github.com/user-attachments/assets/e8ca3e7b-6034-46c0-9e74-2f926414a380" />
<img width="1905" height="800" alt="Screenshot 2025-12-27 224007" src="https://github.com/user-attachments/assets/6d225ece-771f-4738-a3f3-f7fc9527b5ce" />

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
