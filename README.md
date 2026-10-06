# Aditya Patel - Personal Portfolio Website
This assignment is a personal portfolio website created using HTML5 and CSS. The website was created to showcase information about me, my previous projects, and my web development experience.

The website contains 4 HTML pages: Index, About Me, My Projects, and Contact Me

The website uses semantic HTML5 elements such as: `header`, `nav`, `main`, `article`, `section`, `aside`, `footer`, and `address`.

## Website Pages

### Home Page

The Home page introduces my portfolio and provides navigation to the other pages of the website. It includes a top navigation menu and navigation boxes that allow users to visit the Home, About Me, My Projects, and Contact Me pages.

### My Projects Page

The My Projects page displays projects and assignments that I have completed during my studies. The projects include work involving Python programming, computer networking, corporate network design, EIGRP
routing, and other networking and programming concepts. Each project includes a heading and a short description.

### Contact Me Page

The Contact Me page contains an HTML5 form that visitors can use to enter their information and comments.

The form includes:
First Name
Last Name
Email
Cell Number
Comments
Mailing List option
Portfolio source selection
Country selection
Recommendation option
Reset button
Submit button

## Responsive and Fluid Design

The website uses responsive and fluid web design so that it can be viewed on different screen sizes. Percentage-based widths are used throughout the CSS to allow page elements to adjust to the available
screen space.


Three separate CSS files are used:

`full.css` - Laptop/Desktop
`tablet.css` - Tablet
`phone.css` - Mobile Phone
 
### Laptop/Desktop Viewport

The laptop/desktop stylesheet is used for screens with a minimum width of 960 pixels.

``` text
min-width: 960px
```
The desktop layout uses a two-column design. The navigation area is displayed on the left side of the page and the main content is displayed on the right.

### Tablet Viewport

The tablet stylesheet is used for screens between 481 pixels and 960
pixels.

``` text
min-width: 481px
max-width: 960px
```
These dimensions were selected for medium-sized screens such as tablets. The layout uses more of the available screen width, and the navigation
and main content are adjusted so they are easier to read on a smaller screen.

### Mobile Phone Viewport

The phone stylesheet is used for screens up to 480 pixels wide.

``` text
max-width: 480px
```

This dimension was selected for smaller mobile screens. The mobile version uses a single-column layout. Floats are removed, and the navigation, main content, images, video, projects, and form are adjusted
to fit the smaller screen.

Flexbox was not used in the website.

## CSS Gradient

### Radial Gradient

A radial gradient was implemented on the navigation boxes. These are the boxes containing the Home, About Me, My Projects, and Contact Me links.

The gradient was created using the ColorZilla Gradient Editor:
https://colorzilla.com/gradient-editor/#f7fbfc+0,d9edf2+40,add9e4+100;Blue+3D+%231

The following CSS is used for the gradient:

``` css
.box
{
    /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#f7fbfc+0,d9edf2+40,add9e4+100;Blue+3D+%231 */
background: radial-gradient(ellipse at center, rgba(247,251,252,1) 0%,rgba(217,237,242,1) 40%,rgba(173,217,228,1) 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
}
```
The radial gradient changes from a very light blue in the center to a darker light-blue colour toward the outside of each navigation box. The
gradient is implemented in the `.box` class in the CSS stylesheets.


## Adobe Color Palette

The website colour scheme was selected using Adobe Color.

Adobe Color - My Color Theme:
https://color.adobe.com/explore?q=tech&color-palette=CCCFD5%2CFFFFFF%2C4682B4%2C22232E%2C3DBF56&color-palette-name=My+Color+Theme


The palette contains the following colours:

`#CCCFD5` - Light Gray
`#FFFFFF` - White
`#4682B4` - Blue
`#22232E` - Dark Gray/Blue
`#3DBF56` - Green

### How the Colours Were Used
`#CCCFD5` is used for the main page background and some form
borders.

`#FFFFFF` is used for the main content background, navigation
background, and text on dark backgrounds.

`#4682B4` is used for blue headings, project borders, buttons, and
other design elements.

 `#22232E` is used for the header, footer, and dark text.
 
 `#3DBF56` is used as an accent colour for borders, links, hover
effects, and other highlighted elements.


I chose this palette because it has a technology-themed appearance that fits the purpose of my portfolio as a Networking and IT Security student. The dark blue and gray colours give the website a professional
appearance, while green is used as an accent colour to make important elements stand out.

The same colour palette is used throughout the Home, About Me, My Projects, and Contact Me pages to maintain a consistent design.

## HTML5 and CSS3 Features

The website uses HTML5 and CSS3 features including:

Semantic HTML5 elements
HTML5 video
HTML5 forms
HTML5 form validation
CSS radial gradient
Fluid layouts
Percentage-based widths
Responsive design
Separate stylesheets for different viewport sizes
CSS hover effects
Responsive images and video


## Accessibility

The website is tested using the WAVE Web Accessibility Evaluation Tool.

Accessibility features used throughout the website include:
Alternative text for images
Labels for form fields
Semantic HTML5 elements
Clear navigation links
Readable text and background colours
Proper page headings

The website is reviewed to identify and correct accessibility problems where possible.

## Validation and Testing

The website is checked for:
HTML validation
CSS validation
Working navigation links
Form validation
Responsive layouts at different screen sizes
Spelling
Accessibility using WAVE


The website is tested at mobile, tablet, and laptop/desktop viewport
sizes.

## External Code and Sources

Most of the HTML and CSS code used in this website was written by me and was based on concepts and examples taught in the course lectures and tutorials.


The radial gradient code used for the navigation boxes was generated using the ColorZilla Gradient Editor and was implemented in the `.box`
CSS class.


Source: ColorZilla Gradient Editor\
URL:
https://colorzilla.com/gradient-editor/#f7fbfc+0,d9edf2+40,add9e4+100;Blue+3D+%231

The website colour palette was selected using Adobe Color.


Source: Adobe Color
Palette: High Tech Bright Life
URL:
https://color.adobe.com/explore?q=tech&color-palette=CCCFD5%2CFFFFFF%2C4682B4%2C22232E%2C3DBF56&color-palette-name=My+Color+Theme


## GitHub and Version Control

Git and GitHub are used for version control during the development of this portfolio. The repository contains the HTML, CSS, images, video, and other files required for the website.

Changes are committed throughout development to show the major stages and updates to the project.

The completed repository is made public, and the website is deployed using GitHub Pages.

### GitHub Repository
https://github.com/adityapatel2007/Portfolio-Aditya-Patel

### Live GitHub Pages Website
Homepage/Index: https://adityapatel2007.github.io/Portfolio-Aditya-Patel/
About Me: https://adityapatel2007.github.io/Portfolio-Aditya-Patel/aboutme.html
My Projects: https://adityapatel2007.github.io/Portfolio-Aditya-Patel/projects.html
Contact Me: https://adityapatel2007.github.io/Portfolio-Aditya-Patel/contact.html

## Author

Aditya Patel\
Networking and IT Security\
Ontario Tech University

Email: aditya.patel8@ontariotechu.net

## Copyright
Copyright © 2026 Aditya Patel


