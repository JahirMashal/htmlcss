#display a text on top of an image using an overlay


<!DOCTYPE html>
<html>
<head>
    <style> 
 
        div {
          position: relative;
        }
        
        .text-overlay {
          position: absolute;
          top: 0;
          left: 0;
          padding: 1rem;
          font-size: 2rem;
          font-weight: 100;
          color: 
        white;
          backdrop-filter: blur(8px) brightness(80%);
        }
        
        </style>




  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Using HTML, CSS create display a text on top of an image using an overlay</title>
</head>
<body>
<div>
  <h3 class="text-overlay">Hello, World</h3>
  <img src="https://www.w3resource.com/html-css-exercise/html-css-practical-exercises/flower-1.jpeg" height="200" width="200"></div>

</body>
</html>
