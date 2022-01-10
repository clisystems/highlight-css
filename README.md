# highlight-css
Highlight CSS library
A simple CSS library for highlighting elements without affecting spacing.  Useful for debugging and UI development

## Need
When developing UI nested elements become difficult to troubleshoot.  Using Highlight CSS, link a single file and add
HL- classes directly to elements to add a colored border inside the element.  This library uses the CSS outline 
and outline-offset properties to draw a border inside the element to not affect margin, padding or placement.

## Usage
Include the highlight.css to your page:

```html
<head>
<!-- other stuff -->
<link rel="stylesheet" href="highlight.css">
</head>
```

Add classes to create highlights

Red, Green, and Blue highlights:
```html
<body>
<link rel="stylesheet" href="highlight.css">
<div class="HL-red" style='width:100px'>Red</div>
<div class="HL-green" style='width:100px;height:50px;'>Green</div>
<div class="HL-blue" style='width:100px'>blue</div>
</body>
```

Red, Green, and Blue 2px highlights:
```html
<body>
<link rel="stylesheet" href="highlight.css">
<div class="HL-red-2" style='width:100px'>Red</div>
<div class="HL-green-2" style='width:100px;height:50px;'>Green</div>
<div class="HL-blue-2" style='width:100px'>blue</div>
</body>
```

Library also has HL-color-bg classes to fill backgrounds
```html
<body>
<link rel="stylesheet" href="highlight.css">
<div class="HL-red-bg" style='width:100px'>Red</div>
<div class="HL-green-bg" style='width:100px;height:50px;'>Green</div>
<div class="HL-blue-bg" style='width:100px'>blue</div>
</body>
```
