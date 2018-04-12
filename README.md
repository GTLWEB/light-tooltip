# light-tooltip
Jquery extremely light tootip, display on hover element, follow mouse

# how to use
--- You have to load jquery <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
1) Load tooptip.js in your project <head></head>
2) Add attribute data-tooltip to any element

#Example with CSS
```HTML
<html>
  <head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="tooltip.js"></script>
    <link rel="stylesheet" type="text/css" href="tooltip..min.css">
    <style>
      .div-tooltip {display:none; position:absolute; border:1px solid #333;  background-color:#161616; border-radius:5px; padding:10px; color:#fff; font-size:12px Arial; }
    </style>
  </head>
  <body>
    <span data-tooltip="I'm a tooltip message">hover me</span>
  </body>
</html>
```
