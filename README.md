# Animation Download Button Design

This repository contains code for an animated download button designed using HTML, CSS, and JavaScript. The button is created to facilitate the download of an animation displayed on the screen.

## Button Features
- **Background Image:** Utilizes a globe image from Google's Earth API.
- **Foreground Image:** A gradient that fades from black to the button's color, enhancing visual appeal.
- **Interaction:** The button triggers an on-click JavaScript function to initiate the download of the animation.

## Preview
![Animation Download Button](/path/to/animation-download-button.gif)

## How to Use
1. Clone this repository to your local machine.
2. Open the `index.html` file in your browser.
3. Click the download button to initiate the animation download.

## Code Snippet

### HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Animation Download Button</title>
</head>
<body>
  <button id="downloadBtn" onclick="downloadAnimation()">Download Animation</button>
  <script src="script.js"></script>
</body>
</html>
