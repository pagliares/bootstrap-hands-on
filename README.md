# Bootstrap Hands-on

This hands-on focus on CSS version of BootStrap.

## Outline

<a href="https://github.com/pagliares/bootstrap-hands-on#01---bootstrap-and-bootstrap-icons-cdn-template">01 - Bootstrap and Bootstrap Icons CDN template</a><br>
<a href="https://github.com/pagliares/bootstrap-hands-on#02---bootstrap-icons">02 - Bootstrap icons</a><br>
<a href="https://github.com/pagliares/bootstrap-hands-on#03---reboot">03 - Reboot</a><br>
<a href="https://github.com/pagliares/bootstrap-hands-on#04---bootstrap-containers">04 - Bootstrap containers</a><br>
<a href="https://github.com/pagliares/bootstrap-hands-on#05---bootstrap-colors">05 - Bootstrap colors</a><br>
<a href="https://github.com/pagliares/bootstrap-hands-on#06---bootstrap-spacing-padding">06 - Bootstrap spacing (padding)</a><br>
<a href="https://github.com/pagliares/bootstrap-hands-on#07---bootstrap-spacing-margin">07 - Bootstrap spacing (margin)</a><br>

## Examples

### 01 - Bootstrap and Bootstrap Icons CDN template
- <a href="https://github.com/pagliares/bootstrap-hands-on#outline">Back to Outline</a>
- This example presents a <strong>web document template</strong> that includes <strong>Bootstrap</strong> and <strong>Bootstrap icons</strong> declarations on it's head element.
- The template is reused in all other examples in this repo.

### 02 - Bootstrap icons
- <a href="https://github.com/pagliares/bootstrap-hands-on#outline">Back to Outline</a>
- Bootstrap icons: https://icons.getbootstrap.com
- Bootstrap icons is a free library from the creators of Bootstrap
- The example demonstrates:
  - How to include Bootstrap icon using CDN
  - How to add an icon using fonts
  - How to add an icon using SVG
  - How to change the icon color and size
  - How to adjust spacing

### 03 - Reboot
- <a href="https://github.com/pagliares/bootstrap-hands-on#outline">Back to Outline</a>
- For more details on Reboot, visit: https://getbootstrap.com/docs/5.2/content/reboot/
- This example includes 2 web documents box-sizing.html and inherit.html that present some improvements and defaults used by Bootstrap concerning a collection of element-specific CSS changes.
- In other words, Bootstrap has a set of styles called reboot that attempts to create a consistent baseline across different browsers.
- Among Reboot improvements, Bootstrap modifies browser defaults to use <strong>rems instead of ems</strong>. 
  - This makes the defaults a lot more consistent because <strong>rems</strong> or <strong>root ems</strong> are sized according to the default size of the page, which is usually <strong>16 pixels</strong>.
   - <strong>sEms</strong> on the other hand are relative to the size of their containers, so the size of elements is more consistent when using <strong>rems</strong>.
- Another key improvement that affects your pages is that <strong>reboot removes margin top from almost all elements</strong>. 
  - Margins and HTML collapse, so if you have a headline with 10 pixels of margin at the bottom next to a paragraph with five pixels of margin at the top, the size of the margin isn't 15 but 10. 
  - In other words, it ignores the smaller margin. 
  - By resetting margins to the bottom only, there's less of a chance of having to guess, which elements controls the margin. 
- A third improvement is that almost all styles are set to inherit from their parents. This means that bootstrap is much easier to style.

<strong>Bootstrap defaults</strong>:
- Native sans-serif fonts
- Body background: #fff
- Box sizing: border-box

- The problem of not using border-box as the default for box sizing (see box-sizing.html) is that the padding gets added to the size, so the box is actually 520 pixels, 500 plus 10 on each side. 
  - This is terrible, because normally when you say you want something to be 500 pixels wide, you actually expect it to be 500 pixels wide. 
- There's a lot of other modifications and reboot but these are probably the most important to note.  

### 04 - Bootstrap containers
- <a href="https://github.com/pagliares/bootstrap-hands-on#outline">Back to Outline</a>
- For more details on Bootstrap containers, visit: https://getbootstrap.com/docs/5.2/layout/containers/
- <strong>container</strong> is probably the most important class in Bootstrap.
- This example contains a series of containers. You can see that the <strong>container-fluid class</strong> is always going to be the full width of the the viewport, except for a little bit of margin on each side.
- if you make this viewport smaller, hiting predefined Bootstrap breakpoints (see image below), at some point, the <strong>container-xxl</strong>, <strong>container-xl</strong>, <strong>container-lg</strong>, <strong>container-md</strong>, <strong>container-sm</strong>, and <strong>container</strong> classes will actually convert to be a 100% of the width of the viewport.
  - if you go the other way, increasing the width of the viewport, you can see the same happens in reverse. 

<p align="center"><img src="https://github.com/pagliares/bootstrap-hands-on/blob/main/Images/bootstrap-containers.png" width=824 heigh=323></p>

### 05 - Bootstrap colors
- <a href="https://github.com/pagliares/bootstrap-hands-on#outline">Back to Outline</a>
- For more details on Bootstrap colors, visit: https://getbootstrap.com/docs/5.2/customize/color/
- This examples consists of two web documents (index-with-bootstrap.html and index-without-bootstrap.html). 
  - The former presents the web document without bootstrap colors applied
  - The second web document applies several Bootstrap color classes.
- Features described in the example:
  - How to apply <strong>background colors</strong> to HTML elements using Bootstrap <strong>using bg-{color}</strong>, where color can be, for instance, <strong>primary</strong>, <strong>secondary</strong>, <strong>danger</strong>, etc.
  - How to apply <strong>text colors</strong> to HTML elements using Bootstrap <strong>using text-{color}</strong>, where color can be, for instance, <strong>primary</strong>, <strong>danger</strong>, <strong>warning</strong>, etc.
    - How to apply <strong>link colors</strong> to HTML elements using Bootstrap <strong>using link-{color}</strong>, where color can be, for instance, <strong>primary</strong>, <strong>info</strong>, <strong>light</strong>, etc.
    - How to use <strong>color variables</strong> to HTML elements, for instance, <strong>--bs-blue</strong>, </strong>--bs-white</strong>, <strong>--bs-greeen</strong>
- In particular, the example demonstrates how to:
  - Add color to a text
  - Change a background color
  - Change link color
  - Use color variable
  - Redefine a color

### 06 - Bootstrap spacing (padding)
- <a href="https://github.com/pagliares/bootstrap-hands-on#outline">Back to Outline</a>
- For more details on Bootstrap spacing (padding), visit: https://getbootstrap.com/docs/5.2/utilities/spacing/
- Bootstrap includes a wide range of shorthand responsive margin, padding, and gap utility classes to modify an element’s appearance.
- This example concentrates on padding.

<strong>Syntax for padding</strong>

p{DIRECTION}-{AMOUNT}

where:

- DIRECTION may be: t e b s x y 
  - t = top, e = end, b = bottom, s = start, x = x axys, y = y axys
- AMOUNT may be: 0 1 2 3 4 5


### 07 - Bootstrap spacing (margin)
- <a href="https://github.com/pagliares/bootstrap-hands-on#outline">Back to Outline</a>
- For more details on Bootstrap spacing (padding), visit: https://getbootstrap.com/docs/5.2/utilities/spacing/
- Bootstrap includes a wide range of shorthand responsive margin, padding, and gap utility classes to modify an element’s appearance.
- This example concentrates on margin.

<strong>Syntax for margin</strong>

m{DIRECTION}-{AMOUNT}

where:

- DIRECTION may be: t e b s x y 
  - t = top, e = end, b = bottom, s = start, x = x axys, y = y axys
- AMOUNT may be: 0 1 2 3 4 5 auto




