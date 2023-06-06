#Code Refactoring

This is my submission for Homework-1 for NWU's coding bootcamp of Summer 2023. For this assignment, students are tasked to refractor this existing webpage to optimize functionality and accessibility for the search engine. For the final submission, I have added and committed my contributions, and will be merging it onto the main repository. 

## Horiseon Website

This webpage is to help focus on what services Horiseon has to offer. As users hover through the navigation bar on the top right of the page, they will find that each section is linked to the corresponding ID of the page, and taken to the ID when clicking on the buttons. 

## User Story
```
AS A USER of COMPANY,

I WANT a descriptive title
SO THAT is it optimized for the search engine.

I WANT to see visual changes to the font on the navigation list in the header when the user hovers over the words.
SO THAT it allows the user to know that they are links. 

I WANT to select the links on the navigation list when I hover over it 
SO THAT it will take me to the section of the page, rather than scrolling down. 

I WANT the webpage to be complaint with accessibility standards
SO  THAT it is optimized for search engines.

I WANT to view the HTML source code in semantic structure
SO THAT it follows a logical order indpendent of styling.

I WANT to see alt attirbute descriptions of every image when I hover over images
SO THAT if the webpage cannot load, I am still able to find the description of the images and icons. 
```

## What you will find
```
WHEN I view the HTML title properties
THEN I find that the title of this webpage is Horiseon Home Page

WHEN I see and hover for Span 'SEO' in the header
THEN I can click on the link to see the correlation section

WHEN I view the top left navigation elements
THEN I can see that the font style bolds when I hover and interact with the buttons
THEN I can click and it will take me to the correct ID divisions

WHEN I click on the navigation bar
THEN I will see that the page is smooth scrolling down to the ID 

WHEN I inspect the images and icons on the page
THEN I will find the alt attibutes

WHEN I view HTML and CSS
THEN I will find thee semantic structure of the code. 
```
## What it looks like
URL: https://gdonna.github.io/Dgoon-Class-Homework2023/
This is want the page looks like when I have committed the changes:
![This is my refractored attempt to the Horiseon webpage](./assets/127.0.0.1_5500_Develop_index.html.png)

## Challenges I had
I believe this page would benefit from the following for a more user-friendly experience:

* Adding a Fixed 'TOP PAGE' Image to the bottom right 0,0 of the page to link to the .header to allow easier scrolling back to the top of the page. 
* Adding @media screen to max-width of 768px, so that it the navigation elements turns into a flex display column when screen is smaller than 768px.
