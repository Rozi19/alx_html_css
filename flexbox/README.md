<h1>Flexbox</h1>
<h2>0. Add display flex</h2>
<p>In this question Add row class selector <strong>.row{}</strong> and add a property display value flex <strong>display: flex;</strong>.</p>
<p>Now, all children from the row class are flex items</p>
<p>Entirely remove the row::after declaration</p>
<p>Remove the float: left inside [class*='col-'] </p>
<p>All elements should appear same than before using the float</p>
<h2>1. Add new classes on sections</h2>
<p>Using the files from the previous task as the base for this task:
<br>
In the outermost section tag for services
<br>
Add the class section-services
<br>
In the outermost section tag for works
<br>
Add the class section-works
<br>
In the outermost section tag for about
<br>
Add the class section-about-us
<br>
In the outermost section tag for latest_news
<br>
Add the class section-latest-news
<br>
In the outermost section tag for testimonial
<br>
Add the class section-testimonial
<br>
In the outermost section tag for contact
<br>
Add the class section-contact
</p>
<h2>2. Reverse order Latest news cards</h2>
<p>The flex-direction property says how flex items are placed on the main axis and their direction (normal or reversed).
<br>
flex-direction is sometimes used when doing responsive design. Some elements may appear better when they are in column mode on mobile and row when on desktop.
<br>
row-reverse and column-reverse should be used in specific situation. The visual order of elements should be the same visually and in the HTML code. Refer to flex-direction - CSS: Cascading Style Sheets | MDN for more information
<br>
In your CSS file:
<br>
Before /*** 4. CARD ***/, add a new comment: /* Section Latest news ============================= */
<br>
Under that comment section, target the row class inside section-latest-news class
<br>
Property: flex-direction, Value: row-reverse</p>
<h2>3. Simplify services list</h2>
<p>flex-wrap is a property that can force the flex items to be in one or multiple lines. Learn more about it here.
<br>
In the Services section of 3-index.html, remove the second ul and put the 3 lielements under the first ul
<br>
Now, in your CSS file, before /*** 4. CARD ***/, add a new comment: /* Section SERVICES ============================= */
<br>
Under that comment section, add a new selector targeting the row class inside the section-services class
<br>
Property: flex-wrap, Value: wrap </p>
<h2>4. Playing around with the spacing between flex service items</h2>
<p>Using the files from the previous task for this task:
<br>
In 4-styles.css file, within the Grid section
<br>
In .col-1-3 selector
<br>
Replace the current width with calc((100% / 3) - 2rem)
<br>
In .col-1-2 selector
<br>
Replace the current width with calc((100% / 2) - 2rem)
<br>
In [class*='col-']
<br>
Remove the padding declaration
<br>
Set Property: margin to 1rem
<br>
In ul.row declaration
<br>
Replace the current margin with -1rem</p>
<h2>5. Flexify the header</h2>
<p>Using the files from the previous task for this task:
<br>
In your 5-index.html file, inside the Header section
<br>
Wrap the div with class header-logo and the div with class navbar-menu with a div that has header-container as a class
<br>
In your 5-styles.css file,
<br>
Inside the /* Header section<br>
Add a selector for the header-container class<br>
Property: display, Value: flex <br>
Property: justify-content, Value: space-between<br>
Remove header-logo and header-logo a rules<br>
Remove the navbar-menu rule
<br>
In the variables section
<br>
Remove<br>
header-logo-position <br>
header-logo-link-display <br>
header-logo-link-position <br>
header-logo-link-top <br>
header-logo-link-left <br></p>
<h2>6. Flexify the navbar</h2>
<p> in 6-styles.css, inside the /* Navbarsection
<br>
In the nav class selector<br>
Property: display, Value: flex <br>
Inside the .nav .nav-item selector, remove the display declaration <br>
Target .nav-item + .nav-item inside nav class <br>
Move the margin declaration from .nav .nav-item inside the new selector. <br>
In the variables section <br>
Change the value of the variable nav-item-margin to be 0 0 0 2rem
</p>
<h2>7. Align center logo and navbar</h2>
<p> In 7-styles.css, inside the /* Header section, in the header-container class selector, set the property align-items to center</p>
</p>