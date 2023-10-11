## Logo Centered and Dynamically Resized

To display a logo in the middle of the screen and dynamically resize it to fit the viewport, we'll use HTML and CSS.

### index.html

```html
<!DOCTYPE html>
<html>
<head>
  <title>Casual Builder</title>
  <style>
    body, html {
      height: 100%;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #f0f0f0; /* Change the background color as needed */
    }
    #logo {
      max-width: 100%;
      max-height: 100%;
      width: auto;
      height: auto;
    }
  </style>
</head>
<body>
  <img id="logo" src="assets/img//logo.png" alt="Casual Builder logo">
</body>
</html>
