# A-0524 HTML Exercise: Box Model and Positioning

## Objective

Create a simple webpage layout using HTML and CSS to practice the box model and positioning concepts. By the end of this exercise, you will be able to create a webpage with well-structured elements, styled using the box model properties, and positioned using various CSS positioning techniques.

## Instructions

### Step 1: Set Up Your Project

1. **Create the HTML and CSS files:**
   - Create an HTML file named `index.html`.
   - Create a CSS file named `styles.css`.

### Step 2: HTML Structure

2. **Create the HTML Structure:**
   - Open `index.html` and set up the basic HTML structure:

     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Box Model and Positioning Exercise</title>
       <link rel="stylesheet" href="styles.css">
     </head>
     <body>
       <div class="container">
         <div class="box1">Box 1</div>
         <div class="box2">Box 2</div>
         <div class="box3">Box 3</div>
       </div>
     </body>
     </html>
     ```

### Step 3: CSS Styling

3. **Set Up the Container:**
   - In `styles.css`, set up the basic styling for the `.container` class:

     ```css
     .container {
       width: 80%;
       margin: 0 auto;
       border: 2px solid #000;
       padding: 20px;
       box-sizing: border-box;
       position: relative; /* Required for absolute positioning within it */
     }
     ```

4. **Style the Boxes:**
   - Style the individual boxes (`.box1`, `.box2`, `.box3`) using the box model properties:

     ```css
     .box1, .box2, .box3 {
       border: 2px solid #007BFF;
       padding: 20px;
       margin: 10px 0;
       box-sizing: border-box;
     }
     ```

   - Apply different background colors to each box:

     ```css
     .box1 {
       background-color: #FFDDC1;
     }

     .box2 {
       background-color: #C1FFD7;
     }

     .box3 {
       background-color: #C1D4FF;
     }
     ```

5. **Typography and Box Size:**
   - Add some styling for the text inside the boxes and set a fixed height for each box:

     ```css
     .box1, .box2, .box3 {
       font-family: Arial, sans-serif;
       font-size: 16px;
       height: 100px;
       display: block;
       text-align: center;
       line-height: 100px; /* Vertically center the text */
     }
     ```

### Step 4: Positioning
6. **Relative Positioning:**
   - Make `.box1` use `relative` positioning and move it slightly down and to the right:

     ```css
     .box1 {
       position: relative;
       top: 10px;
       left: 10px;
     }
     ```

7. **Absolute Positioning:**
   - Make `.box2` use `absolute` positioning and place it at the bottom right of the `.container`:

     ```css
     .box2 {
       position: absolute;
       bottom: 20px;
       right: 20px;
     }
     ```

8. **Fixed Positioning:**
   - Make `.box3` use `fixed` positioning and place it at the top left corner of the viewport:

     ```css
     .box3 {
       position: fixed;
       top: 20px;
       left: 20px;
     }
     ```

### Step 5: Additional Styling

9. **Add Hover Effects:**

   - Add hover effects to change the background color of each box when the mouse hovers over it:

     ```css
     .box1:hover {
       background-color: #FFB6A3;
     }

     .box2:hover {
       background-color: #A3FFBA;
     }

     .box3:hover {
       background-color: #A3BAFF;
     }
     ```

### Submission

Commit and push your changes once you are done!
