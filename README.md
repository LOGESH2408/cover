# Ex.05 Book Cover Page Design
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contrast Book Cover</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1f1f1f; /* Dark background for more contrast */
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .book-cover {
            width: 300px;
            height: 450px;
            background-color: #1b3a4b; /* Dark blue for a professional, clean look */
            color: #ffffff; /* White text for maximum contrast */
            text-align: center;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.6); /* Stronger shadow for depth */
        }

        .book-cover h1 {
            font-size: 30px;
            margin: 0;
            font-weight: bold;
            color: #FF6347; /* Tomato red for the title to stand out */
        }

        .book-cover h2 {
            font-size: 18px;
            margin-top: 10px;
            color: #FFD700; /* Gold color for the subtitle */
        }

        .book-cover .author {
            font-size: 16px;
            margin-top: 20px;
            color: #ADD8E6; /* Light blue for the author's name */
        }

        .book-cover .image {
            background-color: #2F4F4F; /* Dark slate gray background for the image placeholder */
            height: 180px;
            margin-top: 20px;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="image"></div>
        <h1>The Mysterious Forest</h1>
        <h2>A Journey Beyond</h2>
        <div class="author">by LOKESH</div>
    </div>

</body>
</html>

```                                                                                                                                                                                                                                  


## OUTPUT:


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
