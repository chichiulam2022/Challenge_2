# Challenge #1: Professional Portfolio by Chi Chiu Lam

https://chichiulam2022.github.io/my-webpage/

This is my first portfolio website that contains my coming-up projects. I would like to make my website bilingual (potentially in another language in the future) in order to reach out different audience.

Some features used in my website:

1.  `:hover` pseudo-classes for the buttons, navbar, navbar links, form, and social media icon
2.  `flex` and `@media` for responsive layout (may not be too perfect at this time for all devices)
3.  `:root` for grouping reusable variables in CSS
4.   use Google Fonts
5.   use animated icons provided by Font Awesome
6.   use the Favicon generator for the browser tab
7.   use `transition` for simple animations
8. use the second `index_fr.html` for the French version

## Code Examples

* `:hover`
```css
.logo:hover {
    color: var(--main-color);
    transition: 0.3s ease-in;
}
```

* `:root`
```css
:root {
    --content-color: #ff00ff;
    --main-color: #5900b3;
    --second-color: #330033;
    --third-color: #33001a;
}
```

* create a form
```html
<form>
    <div class="input-group">
       <label for="your-name">Your Name&nbsp&nbsp<i class="fa-solid fa-user"></i></label>
       <input type="text" id="your-name" name="your-name" placeholder="Full Name" required>
    </div>
</form>                  
```
* use of a new pseudo-element `::before`
```css
.lang-menu ul li a::before {
        display: none;
}
```
