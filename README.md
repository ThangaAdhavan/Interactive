# Ex.08 Design of Interactive Image Gallery
## Date:04.10.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Image Gallery</title>
</head>
<body background="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\720ba5a318353c073182503ea8232d3a.webp">
    <header style="text-align: left; background-color: black; color: rgb(255, 255, 255); padding: 3rem 0;font-size: 99px;font-style: oblique;">
        <h1>DRAGON BALL Z KAI</h1>
    </header>
    

    <div style="white-space: nowrap; overflow-x: auto; padding: 10rem;">
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <img src="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\2b13e018-8a60-4bb8-9d71-f77d9790bf04.jpg" height="600px" width="325px">
        </div>
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <img src="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\6a4e6d26-6960-4df7-8a38-356c80635888.jpg" height="600px" width="525px">
        </div>
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <img src="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\f36a3f20-c411-49b6-a2e1-efa4c5d7e0dc.jpg" height="600px" width="525px">
        </div>
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <img src="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\download.jpg" height="600px" width="899">
        </div>
    </div>
    <div style="white-space: nowrap; overflow-x: auto; padding: 10rem;">
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <img src="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\Ultra Vegito blue PC Wallpaper.jpg" height="600px" width="850px">
        </div>
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <img src="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\455b2417-7804-408c-b1a0-578bb48370e5.jpg" height="600px" width="525px">
        </div>
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <img src="C:\Users\Adhavan\Interactive\imagegallery\imageapp\static\7346e10d-100b-4468-9b12-540db1ece6b8.jpg" height="600px" width="525px">
        </div>
        <div style="display: inline-block; margin-right: 150px;" onclick="openModal(this)">
            <iframe src="https://assets.pinterest.com/ext/embed.html?id=110901209570322183" height="560" width="345" frameborder="2" scrolling="yes" ></iframe>
        </div>
    </div>

    <div id="modal" style="display: none; position: fixed; z-index: 1; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.9);">
        <span style="position: absolute; top: 15px; right: 35px; color: white; font-size: 40px; font-weight: bold; cursor: pointer;" onclick="closeModal()">&times;</span>
        <img id="modalImage" style="display: block; margin: 5% auto; max-width: 80%;">
    </div>

    <script>
        function openModal(element) {
            var modal = document.getElementById("modal");
            var modalImg = document.getElementById("modalImage");
            modal.style.display = "block";
            modalImg.src = element.querySelector("img").src;
        }

        function closeModal() {
            document.getElementById("modal").style.display = "none";
        }
    </script>
</body>
</html>
```

## OUTPUT:
![alt text](<imagegallery/imageapp/static/Screenshot (6).png>)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
