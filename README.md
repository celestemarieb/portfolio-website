## Overview 

### Portfolio website is published here: 

https://celestemarieb.github.io/portfolio-website/

### Github repository: 

https://github.com/celestemarieb/portfolio-website

### Description 

A personal portfolio highlighting: 
- blog posts 
- information about my skills, experience and interests 
- recent work 
- how I can be contacted 

The portfolio is a publicly accessible website that can be viewed on all devices and screen-sizes. 

### Purpose

This portfolio is designed to introduce myself and my interests as well outline relevant skills, projects and experience. 

### Target Audience 

This website is intended to showcase my skills, experience and interests to like-minded folk who may have similar interests or a need for my skills. 

## Features 

### Responsive 

The website is optimised for use on both mobile and desktop. 

When the website is viewed on different screen sizes the content (e.g. images and text) adjusts accordingly. 

### Navigation 

From any page the logo in the top left corner can be clicked to return to the Home page. 

Main pages (Home, About, Work (Projects), Writing (Blog), Contact) can be accessed via a navigation bar. 

Each individual blog and project page can access the navigation bar and return to a main page. 

When viewed on a smaller screen size or mobile (below 600px width) the navigation bar can be accessed via a plus icon in the top right of the screen. A menu slides across providing access to main pages. 

When viewed on a larger screen (above 600px width) the navigation bar can be accessed on the top right corner via a row of links. 

### Galleries 

The site contains two galleries. A blog page (writing) to preview a variety of blog posts and a project page (work) to provide a preview of pages dedicated to individual projects. 

The galleries have a common responsive design. 

Each contains a selection of article preview cards. When hovered over the card 'jumps forward' via a drop shadow effect. 

Each article preview card includes:
- an image
- title 
- description 
- date published
- a button with an internal link to the individual blog or project page

When viewed on a larger screen (above 600px width) the cards are stacked vertically in two columns. 

When viewed on a smaller screen size or mobile (below 600px width) the gallery adjusts in size to show cards stacked vertically in one columns. 

Given the small selection of blog posts and projects currently published this responsive design quickly communicates the breadth of content available by making use of available space. 

### Calls to Action

A call to action section is included on every page. 

This is a collection of buttons linking to relevant external (on the individual project page, to the projects respository on github) 
and internal destinations as well as file downloads (on the about page, a resume pdf can be downloaded) and email creation (on the contact page, an email from the users mail client to a selected contact email address is created). 

Button style and behaviour is consistent across the site. Multiple buttons are stacked vertically. 

When viewed on a smaller screen size or mobile (below 600px width) the call to action section adjusts in size to cover a larger portion of the screen. This is for easy use of the buttons (by thumbs) on mobile devices.  

When viewed on a larger screen (above 600px width) the section inhabits a smaller proportion of the screen and is contained to the bottom left. 

While the call to action remains of a noticeable size and easy to use it does not distract from the various images and content on each page. 

## Design 

### Colour Palette 

The website Coloors was used to select the following overall colour palette. 

--slate-gray: #6b717eff;
--lavender-pink: #efaac4ff;
--electric-blue: #53f4ffff;
--misty-rose: #ffe8e1ff;
--alabaster: #d4dccdff;

This muted palette was chosen as a clean, calming stage for text, images and gallery preview cards to pop against. 

Alabaster and Lavender Pink are used as primary and secondary colours to provide structure. 

Misty Rose serves as a background for longform text to provide maximum contrast for ease of reading. 

Electric Blue is used as an alternative color to inject life and immediacy into the experience. 

This color has been used to add emphasis to gallery preview cards, the mobile/responsive menu and buttons on hover. 

### Text Styles 

Kdam Thmor Pro is used across the website. 

One text style was chosen in order to provide a consistent visual style and minimise distractions for the visitor from the images, content and calls to action (internal and external links). 

### Sitemap 

The website includes the following html pages:

- Home (index.html)
- About  
- Work (Projects) 
  - Project #1 
- Writing (Blog)
    - Blog #1 (Blog Post)
    - Blog #2 (Blog Post)
    - Blog #3 (Blog Post)
    - Blog #4 (Blog Post)
    - Blog #5 (Blog Post)
- Contact 

A diagram below illustrates the relationship between each page and the function of a navigation bar included in the site. 

The hierarchy and file structure of the site is consistent with the diagram. 

The direction of the arrows indicate the hierarchy of pages within the site. 

All pages can access the home page but not all pages can access one another. 

From any page the logo on the top left can be clicked to return to the home page. 

From any page the navigation bar can be accessed to return to any page on the second tier (About, Contact, Blog (Writing), Projects (Writing)). I will refer to these pages as 'main' pages. 

Individual blog and project pages (e.g. Blog One, Project One) are only accessible via the blog and project pages respectively. 

Individual blog and project pages are not accessible via the navigation bar. 

![Portfolio Sitemap](./docs/portfolio.sitemap.png "Portfolio Sitemap")

### Wireframes 

All wireframes created for this project (a pdf file) are accessible here:![All Wireframes](./docs/Wireframes.pdf "All Portfolio Wireframes") 

#### Mobile Wireframes 

All screens under 600px in width viewing the site will have access to the mobile/responsive experience as outlined below. 

[Mobile Home](./docs/Wireframe_Mobile_Home.png "Wireframe Mobile Home") 

The Home page features a large image, text and large buttons to access internal and exernal links. These extend across the full width of the screen. 

In the top right corner the navigation bar/menu can be accessed via the plus icon. 

[Mobile Menu](./docs/Wireframe_Mobile_Menu.png "Wireframe Mobile Navigation")

The navigation bar/menu slides into view when selecting the plus icon. It allows the user to access any main page. It can be closed by reselecting the icon. The menu extends across the full width of the screen. 

[Mobile About](./docs/Wireframe_Mobile_About.png "Wireframe Mobile About") 

This page can be accessed via the navigation bar/menu. The user can return to the home page by clicking the logo in the top left corner. 

It features long form text and large buttons to download a resume and send an email. These extend across the full width of the screen. 

[Mobile Contact](./docs/Wireframe_Mobile_Contact.png "Wireframe Mobile Contact") 

This page can be accessed via the navigation bar/menu. The user can return to the home page by clicking the logo in the top left corner. 

It features text and large buttons to send an email, view a github profile and view a linkedin profile. These extend across the full width of the screen. 

[Mobile Blog](./docs/Wireframe_Mobile_Blog.png "Wireframe Mobile Blog")

This page can be accessed via the navigation bar/menu. The user can return to the home page by clicking the logo in the top left corner. 

It features cards previewing blog posts and includes large buttons to send an email or visit an external link. These extend across the full width of the screen. 

Each card incudes a button(link) to access the blog post. 

The cards are stacked vertically in a single column. 

[Mobile Blog Post](./docs/Wireframe_Mobile_Blog_Page.png "Wireframe Blog Post") 

This page can be accessed via the blog page. The user can return to the home page by clicking the logo in the top left corner. 

It features an image, long form text and large buttons to send an email or visit an external link. These extend across the full width of the screen. 

[Mobile Projects](./docs/Wireframe_Mobile_Projects.png "Wireframe Mobile Projects") 

This page can be accessed via the navigation bar/menu. The user can return to the home page by clicking the logo in the top left corner. 

It features cards previewing projects and includes large buttons to visit a external links. These extend across the full width of the screen. 

Each card incudes a button(link) to access the individual project page. 

The cards are stacked vertically in a single column. 

[Mobile Project Post](./docs/Wireframe_Mobile_Project_Page.png "Wireframe Mobile Project Post") 

This page can be accessed via the projects page. The user can return to the home page by clicking the logo in the top left corner. 

It features an image, long form text and large buttons to visit external links. These extend across the full width of the screen. 

#### Desktop Wireframes 

All screens over 600px in width viewing the site will have access to the mobile/responsive experience as outlined below. 

[Desktop Home](./docs/Wireframe_Desktop_Home.png "Wireframe Desktop Home") 

The Home page features a large image, text and large buttons to access internal and exernal links. 

The navigation bar is placed in the top right corner. The navigation bar is a horizontal list of hyperlinked text. From this bar all main pages can be accessed. 

[Desktop About](./docs/Wireframe_Desktop_About.png "Wireframe Desktop About") 

This page can be accessed via the navigation bar. The user can return to the home page by clicking the logo in the top left corner. 

It features long form text and large buttons to download a resume and send an email. 

[Desktop Contact](./docs/Wireframe_Desktop_Contact.png "Wireframe Desktop Contact") 

This page can be accessed via the navigation bar. The user can return to the home page by clicking the logo in the top left corner. 

It features text and large buttons to send an email, view a github profile and view a linkedin profile. 

[Desktop Blog](./docs/Wireframe_Desktop_Blog.png "Wireframe Desktop Blog")

This page can be accessed via the navigation bar. The user can return to the home page by clicking the logo in the top left corner. 

It features cards previewing blog posts and includes large buttons to send an email or visit an external link. 

Each card incudes a button(link) to access the blog post. 

The cards are stacked vertically in two columns.  

[Desktop Blog Post](./docs/Wireframe_Desktop_Blog_Post.png "Wireframe Desktop Blog Post") 

This page can be accessed via the blog page. The user can return to the home page by clicking the logo in the top left corner. 

It features an image, long form text and large buttons to send an email or visit an external link. The image extends across the full width of the screen. 

[Desktop Project](./docs/Wireframe_Desktop_Projects.png "Wireframe Desktop Projects") 

This page can be accessed via the navigation bar/menu. The user can return to the home page by clicking the logo in the top left corner. 

It features cards previewing projects and includes large buttons to visit a external links. 

Each card includes a button(link) to access the individual project page. 

The cards are stacked vertically in two columns. 

[Desktop Project Post](./docs/Wireframe_Desktop_Project_Page.png "Wireframe Project Post") 

This page can be accessed via the projects page. The user can return to the home page by clicking the logo in the top left corner. 

It features an image, long form text and large buttons to visit external links. The image extends across the full width of the screen. 

### Screenshots 

The deployed version of the general layout for desktop with navigation bar: 

[Desktop General Layout](./docs/Screenshot%20_Desktop_Nav.png "Screenshot Desktop Layout and Navigation") 

The deployed version of the general layout for mobile/smaller screen sizes with navigation icon: 

[Mobile General Layout](./docs/Screenshot_Mobile_Nav_1.png "Screenshot Mobile Layout and Navigation") 

[Mobile Nav Menu](./docs/Screenshot_Mobile_Nav_2.png "Screenshot Mobile Navigation Menu") 

## Tech Stack 

HTML
CSS, flexbox
Deployment Platform : Github Pages

### Tools 

VSCode 
Figma (design including wireframing)
Github (version control)
Github Pages (deployment and hosting)
Github Projects (project management)
Coloors (palette construction)

## Attributions 

Images used on the site are from Unsplash and the following creators: 



Fonts used on the site were designed by Tep Sovichet and Hak Longdey. They are published on Google Fonts and can be found here: https://fonts.google.com/specimen/Kdam+Thmor+Pro. 