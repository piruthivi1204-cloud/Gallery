# Ex.08 Design of Interactive Image Gallery
# Date:08/10/2025
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
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Multiple Images Enlarge on Click</title>
 
<center>
<style>
  .clickable-image {
    width: 150px;
    height: auto;
    margin: 10px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .enlarged {
    transform: scale(2);
    z-index: 10;
    position: relative;
  }
</style>
</head>
<body style="background-color: cyan;">
    <h1>Avengers</h1>

<img class="clickable-image" src="ironman.jpeg" alt="Image 1" />
<img class="clickable-image" src="spider.jpeg" alt="Image 2" />
<img class="clickable-image" src="loki.jpeg" alt="Image 3" />
<img class="clickable-image" src="cap.jpeg" alt="Image 4" />
<img class="clickable-image" src="black.jpeg" alt="Image 5" />
<br>
<br>
<h2>Image Gallery Designed By:</h2>
<h3>Piruthiviraj G (25016420)</h3>
<script>
  const images = document.querySelectorAll('.clickable-image');

  images.forEach(img => {
    img.addEventListener('click', () => {a
      img.classList.toggle('enlarged');
    });
  });
</script>
</center>
</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot 2025-10-08 141754.png>)
# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
