# Ex.06 Book Front Cover Page Design
# Date:01.12.2025
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
<title>Book Mockup</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f2f2f2;
    font-family: Arial, sans-serif;
}

/* Book container */
.book-wrapper {
    position: relative;
}

/* Book shadow */
.book-shadow {
    position: absolute;
    width: 240px;
    height: 360px;
    background: rgba(0,0,0,0.15);
    filter: blur(25px);
    top: 25px;
    left: 25px;
    z-index: 1;
}

/* Book */
.book {
    width: 240px;
    height: 360px;
    background-color: #ffffff;
    box-shadow: 0 10px 25px rgba(0,0,0,0.25);
    position: relative;
    z-index: 2;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 25px 20px;
    box-sizing: border-box;
}

/* Title text */
.book-title {
    text-align: center;
    margin-top: 20px;
}

.book-title small {
    font-size: 10px;
    letter-spacing: 1px;
    color: #999;
}

.book-title h1 {
    font-size: 20px;
    margin: 10px 0 0;
    color: #8faeb2;
    letter-spacing: 2px;
}

/* Image */
.book img {
    width: 100%;
    opacity: 0.85;
}
</style>
</head>

<body>

<div class="book-wrapper">
    <div class="book-shadow"></div>

    <div class="book">
        <div class="book-title">
            <small>INSTANT DOWNLOAD INCLUDED</small>
            <h1>BOOK<br>MOCKUP</h1>
            <small>PHOTOSHOP PSD</small>
        </div>

        <img src="book.png" alt="Book Image">
    </div>
</div>

</body>
</html>
```
# OUTPUT: ![cover](https://github.com/user-attachments/assets/797641c6-f67b-4d6d-9c61-1455e5deb16d)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
