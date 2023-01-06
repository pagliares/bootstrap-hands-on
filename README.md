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
  - Body background #fff
  - Box sizing: border-box
