# uwbootscamphomework2
# Project Name
> Homework 2 - Responsive Portfolio

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Features](#features)
* [Code Style](#code-style)
* [Screenshots](#screenshots)
* [Technology](#technology)
* [Action taken](#Action-taken)
* [Status](#status)
* [Create By](#create-by)

## General info
This project is to bulid a personal portfolio where it will  change of the page content according to the screen size. 

This project consists of the following 3 pages:
1. Home - a self-introduction inside the content of about me
2. Portfolio - a consolidation list for my project
3. Contact me - include a form for vistors who might want to contact me for more infomation to submit

Please visit [https://rickyfuk.github.io/uwbootscamphomework2/](https://rickyfuk.github.io/uwbootscamphomework2/) for the site.

## Screenshots
![screenshot](https://github.com/rickyfuk/uwbootscamphomework2/blob/9e0e8603170b92108b740949b9473dd02093d34f/assets/image/screenshot.PNG?raw=true)

## Features
In this project, the following features have apply to the site:

**Navgation Bar - Apply to all 3 pages (Home/Portofio/Contact)**
1. A navagation bar that allowed the user to navagiate within these 3 pages
2. The style for the page name will change when it is being in the following 4 status:
    -focus (when it is clicked)
    -hover (when the mouse over)
    -active (after the name is clicked)
    -visited (after the page is visited)
3. The page selction on navagation bar will collapse into a toggle button when the screen size is below the medium one. (Please click the button to expand the list)

**Home Page**
1. The paragraph have been justify with full lenght
2. The About me box will be change the layout as follow:
| Screen Size |         Layout           |
|:------------|:-------------------------|
|below med    |one box in the middle     | 
|med to large |one box in the middle     |
|above large  |one box and right aligned |
3. The background image will change when the screen size drop below med
<div>
  <img src="https://github.com/rickyfuk/uwbootscamphomework2/blob/master/assets/image/pexels-photo-1738994-2.jpeg?raw=true" alt="Hong Kong night view">
  *This is the background image for screen size below med*
  <img src="https://github.com/rickyfuk/uwbootscamphomework2/blob/master/assets/image/pexels-photo-1383562.jpeg?raw=true" alt="A black desktop with a tag">
  *This is the background image for screen size above or equal to med*
</div>

4. The Bio image will change the style as follow:
| Screen Size |        Style       |
|:------------|:-------------------|
|below med    |90% of screen width | 
|med to large |Max-width : 250px   |
|above large  |Max-width : 200px   |



4. Put in the amendment details and the better understanding for further developers.



| Screen Size |              layout              |
|:------------|:---------------------------------|
|below med    |one row and the box in the middle | 
|med to large |two rows and the box in the middle|
|above large  |two rows and the box right align  |
The result is expected to eliminate the unneccessary HTML and CSS code and enhance the reader experience for the site.

## Code Style
Standard

## Technology
The following technology have been used for this project:

  1. HTML
  2. CSS
  3. Bootstrap

## Action taken
List of Changes
* Change the title from website to Horiseon Social Solution Services for easier to locate the site by search engine

* HTML
  - Change some of the non-semetic code to semetic one in index.html file include:
    1. 'div class="header"' to 'header'
    2. Change 'div class="content"' into 'section'
    3. Change 'div class="benefit"' into 'aside'
    4. Change 'div class="footer"' into 'footer'
  - Add "ALT" element for all the image
* CSS
  - Retitle the following CSS section from style.css file:
    1. Change ".content" to "section"
    2. Change ".benefit" to "aside" 
    3. Change ".footer" to "footer"
  - Combine the CSS following elements:
    1. ".search-engine-optimization", ".online-reputation-management" and ".social-media-marketing" into one element - "article"
    2. ".benefit-lead", ".benefit-brand" and ".benefit-cost" into one element - ".benefit"


List of other additional action
* Add description for every single part of Html and CSS code
  <div>
  <img src="https://github.com/rickyfuk/uwbootscamphomework1/blob/master/assets/images/descriptionexample.PNG?raw=true" alt="descriptionExample">
  *example for the description*
  </div>
* List out the amendment details for easier understadning to the future developer
  <div>
  <img src="https://github.com/rickyfuk/uwbootscamphomework1/blob/master/assets/images/amendmentexample.PNG?raw=true" alt="amendmentExample">
  *example for the amendment*
  </div>
* Fixed click and navigate function for the "Search Engine Optimation"
  - Add "id = search-engine-optimization" to the article on line 62 
  ```html
       1. Open the html file
       2. Find the following code block on line 61:
          <section>
           <article id= "search-engine-optimization">
  ```
* Fixed the entire content to stick in the original position regardless to the viewer point
  - Add "overflow: auto;" and "min-width:1024px;" to the body CSS section
  
  >     1. Open the CSS file
  >     2. Find the following code block on line 13:
  ```CSS
            body {
               background-color: #d9dcd6;
               overflow: auto;
                min-width:1024px;
               }
  ```


## Status
Project status: finished


## Create By
Created by Chung Hei Fuk

