# Bootstrap Hands-on

This course focus on CSS version of BootStrap.

## Examples

### 01 - Bootstrap and Bootstrap Icons CDN template

- This example presents a <strong>web document template</strong> that includes <strong>Bootstrap</strong> and <strong>Bootstrap icons</strong> declarations on it's head element.
- The template is reused in all other examples in this repo.

### 02 - Bootstrap icons

- Bootstrap icons: https://icons.getbootstrap.com
- Bootstrap icons is a free library from the creators of Bootstrap
- The example demonstrates:
  - How to include Bootstrap icon using CDN
  - How to add an icon using fonts
  - How to add an icon using SVG
  - How to change the icon color and size
  - How to adjust spacing

### 03 - Reboot

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

- For more details on Bootstrap containers, visit: https://getbootstrap.com/docs/5.2/layout/containers/
- <strong>container</strong> is probably the most important class in Bootstrap.
- This example contains a series of containers. You can see that the <strong>container-fluid class</strong> is always going to be the full width of the the viewport, except for a little bit of margin on each side.
- if you make this viewport smaller, hiting predefined Bootstrap breakpoints (see image below), at some point, the <strong>container-xxl</strong>, <strong>container-xl</strong>, <strong>container-lg</strong>, <strong>container-md</strong>, <strong>container-sm</strong>, and <strong>container</strong> classes will actually convert to be a 100% of the width of the viewport.
  - if you go the other way, increasing the width of the viewport, you can see the same happens in reverse. 

<p align="center"><img src="https://github.com/pagliares/bootstrap-hands-on/blob/main/Images/bootstrap-containers.png" width=824 heigh=323></p>
