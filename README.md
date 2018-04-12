# light-tooltip
Jquery extremely light tooltip, display on hover, follow mouse

# how to use
1) Load jQuery and tooptip.js
```HTML
<head>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="tooltip.js"></script>
</head>
```
2) Add attribute data-tooltip to any element
```HTML
<body>
  <button data-tooltip="This is a button">My button</button>
</body>
```

#Example with CSS
```HTML
<html>
  <head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="tooltip.js"></script>
    <link rel="stylesheet" type="text/css" href="tooltip..min.css">
    <style>
      .div-tooltip {display:none; position:absolute; background-color:#000; padding:10px; color:#fff; font-size:12px Arial; }
    </style>
  </head>
  <body>
    <button data-tooltip="This is a tooltip">My button</button>
  </body>
</html>
```
