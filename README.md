# social-media-icons
A customizable, responsive row of social media icons featuring a sleek grayscale-to-color hover effect. Perfect for adding a modern, interactive touch to personal portfolios, business websites, or any web project requiring social media links.


# Social Icons Row

A customizable, responsive row of social media icons featuring a sleek grayscale-to-color hover effect. Perfect for adding a modern, interactive touch to personal portfolios, business websites, or any web project requiring social media links.

## Description

This project provides a customizable row of social media icons (GitHub, Dribbble, and LinkedIn) with the following features:

- Icons are grayscale by default and turn to color on hover
- The GitHub icon has a special gray filter that turns to black and white on hover
- Responsive design that adjusts for mobile devices
- Left-aligned layout

## Usage

1. Copy the HTML and CSS into your project.
2. Customize the icon URLs and links as needed.
3. Adjust the styles to fit your design preferences.

## HTML Structure
html
<div class="social-icons">
<a href="https://github.com" target="blank">
<img src="https://github.com/fluidicon.png" alt="GitHub" class="social-icon github">
</a>
<a href="https://dribbble.com" target="blank">
<img src="..." alt="Dribbble" class="social-icon dribbble">
</a>
<a href="https://linkedin.com" target="blank">
<img src="..." alt="LinkedIn" class="social-icon linkedin">
</a>
</div>


## CSS Highlights
css
.social-icon.github {
filter: grayscale(100%) brightness(180%) contrast(80%);
}
.social-icon.github:hover {
filter: none;
}
.social-icon.dribbble,
.social-icon.linkedin {
filter: grayscale(100%);
}




