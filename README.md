# Fancy Font Flipping
Fancy Font Flipping is a demo I first put up in CodePen to illustrate the issues with flipping the text color from black to white based on a given estimated background luminance. The index.html file here contains the CSS and JS.

## Features
- Flips font color from black to white, depending on background
- Adjust font size based on resultant contrast.
- Secondary sample text in opposite color
- Color picker to set the overall background.

The live CodePen is https://codepen.io/myndex/pen/RwZJyPR

And the live index page here is https://myndex.github.io/fancyfontflipping/

There are a number of constants you can adjust to see how different levels of luminance *or* percepual lightness affect the readability of the text. In conjuction with this, near the middle range, the font is increased in size. This is because small fonts need more contrast than is available between the actual middle contrast (on an sRGB monitor) and either black or white. 

### Example Output
<img src="IMAGES/fancyfontflip1.png">



