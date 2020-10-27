# 20-10-26 CSS Intro Practice

### Note
Create a CSS file and style elements using only the tags/class/ids already available in the provided HTML file. You will need to link the newly created CSS file to the HTMl file provided. If a unit isn't specified (ie border width, padding or margin) choose a size that you think is appropriate and noticeable. 
 
### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode
1. open the provided HTML file using `ctrl o` in the browser

### Linking files
1. create a new css file called `style.css`
2. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
3. check that the files are linked by setting the `background-color` property of the body to any color other than white/gray and refreshing the page

### Tag Selector
1. set the background color to light gray using the body tag selector
1. set the font family to sans-serif using the body tag selector
1. add space between the body and the window using margin
1. center align the text in the heading one element and the header element using the h1 and header tag selectors
1. change the text color of all links using the anchor tag selector
1. give all div elements a thick dark green border using the div tag selector
1. add space between the text and the border on all sides of all div elements using padding
1. add space between div elements outside of the border on the top and bottom using margin
1. give the image a thick black border using the image tag selector
1. set the width of the image to 50% of it's parent element
1. center the image in it's parent element by adding 25% margin on the left and right side 

### Class Selector
1. set the background color of all divs with the class `foodIpsum` to dark green
1. set the text color fo all divs with the class `foodIpsum` to white

### ID Selector
1. center align the text in the paragraph element with the ID `credit`

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation Info on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)

