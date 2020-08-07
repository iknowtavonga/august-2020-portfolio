# August 2020 Portfolio

## Project Purpose
After 30+ days of learning HTML and CSS with projects targeting numerous sections. I decided to put all these lessons to good use by making a portfolio showcasing all the projects i completed while learning
I took this opportunity to implement other css elements i hadn't tried out before such as:

* CSS Grid
* Media queries for full length projects
* Inserting Font awesome icons.
* Sticky Navbar

## Contributors
* Tavonga I Karimanzira

## Home Page Sections
* Welcome section
* Navigation section
* Showcase section
* Project portfolio
* About me 
* Contact me

## Welcome 

The welcome section contains a basic h2 tag with a small description of the website.

## Navigation 

The navbar has the following links:
* Home
* My work
* About me
* Contact me

The navbar is styled to stick to the top of the screen when you scroll down.

## Showcase

The showcase section is styled to fit 100% of the viewport of big devices and 50% of small devices. There is a button at the center of the bigger devices with the following text - "Portfolio". This button does not appear on smaller devices.

The background of the showcase area is an image. This can be any image

## Project portfolio

The portfolio section contains a grid with a project title and a screenshot of the project. The screenshot is enclosed in an a tag. The link redirects to the github page of that project. 

On large screens there are 2 grid columns and on small screens there is only 1.

## About me

The about me section contains details of me and my journey.

## Contact me

The contact me section contains icons of social media sites where i can be contacted and an email address icon. The icons are arranged in a grid.

## Hardest sections

The media queries were the hardest sections in this project because i had to fill in media queries for all the device sizes. Once i had overcomed media query declarations i was able use simple css styles to optimise elements to the various viewports. 

The most important code learnt from this project was the following:

```css
@media (min-width: 426px) and (max-width: 768px){

/* Styling for the media query is inserted here*/

}

```

## Important concepts learnt

Other than media queries the other important concept i learnt from this project was the css grid. This was my first time using css grid outside of a tutorial environment and maintaining the grid on all device viewports was slightly challenging. I was able to optimise the rows using the following code:

```css
#projects{
        grid-template-columns: 1fr;
    }
```

Linking icons from font awesome was another important lesson learnt. Before this lesson my go-to-method for adding such items was to use images. I enclosed the icons in links so that they have functionality. This meant that i had to style the link so it wouldnt make the icon blue. I achieved all this with the code below:

```html
<div id="social-network">
    <a href="https://github.com/iknowtavonga"><i class="fab fa-3x fa-github"></i></a>
</div>
<div id="social-network">
    <a href="https://stackoverflow.com/users/5934374/tavonga"><i class="fab fa-3x fa-stack-overflow"></i></a>
</div>
```
The icons needed to be linked in the header first.

```html
<link rel="stylesheet" href="./css/all.min.css">
```

After linking i had to style the links to change to the default color. I used the following code

```css
#social-network a{
    text-decoration: none;
    color: inherit;
}
```

## Final thoughts

This project allowed me to measure my progress with minimal help from tutorials and i am very happy with that progress. Flexbox has been my go to source of help when i need to move items around and i went a step further by learning css grid. This has also been one of my least challenging projects.

> *"Try try try again until the good is better and the better best* - ***My grade 2 teacher***