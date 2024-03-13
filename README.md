
## Readme.md File Main Purpose.

This document contains information related to the Week Two, Advanced CSS Challenge: Professional Portfolio from the UCF Coding Bootcamp.

Important: The set of skills used to complete this challenge, follows the knowledge gained throughout the second part of the program. New tools and technologies may exist; however, they are not part of this program segment.

The skill's used are flexbox, media queries, and CSS variables.

## Color Reference


| Navigation Bar & Footer | 
<div style="background-color: rgb(41, 72, 100); color: white; padding: 10px;">rgb(41, 72, 100)</div>


| Header Background Color - (Only visible on smaller screens)| 

<div style="background-color: rgb(103, 145, 182); color: white; padding: 10px;">rgb(103, 145, 182)</div>

| Hover Button Color |
<div style="background-color: rgb(189, 184, 184); color: black; padding: 10px;">rgb(189, 184, 184)</div>

## Logo and side Images

- All images used follows the pattern below.

![Logo](https://marciopimentel01.github.io/Portfolio/Assets/Images/hero-png.png)



# HTML Webpage Structure Overview

This section provides an overview of the structure of a simple webpage written in HTML. The webpage consists of various sections including navigation, about me, work experience, projects, contacts, and a footer.

## Document Type Declaration (DOCTYPE):

- Declares the document type and version of HTML being used.

## HTML Element:

- The root element of the HTML page.

## Head Section:

- Contains metadata about the document such as character set, title, links to stylesheets, and potentially scripts.
- Metadata includes the charset, title, and links to external resources like stylesheets.

## Body Section:

- Contains the visible content of the webpage.
- Includes various sections like header, about me, work experience, projects, contacts, and footer.

## Header Section:

- Typically contains the top portion of the webpage, often including a logo and site title.
- Contains a navigation bar with links to different sections of the page.

## Main Content Sections:

### About Me Section:

- Provides information about the individual, including a brief introduction and description.

### Work Experience Section:

- Lists previous work experiences with details like job titles, responsibilities, and durations.

### Projects Section:

- Describes a specific project, including an image, description, and link to more details.

### Contacts Section:

- Provides contact information like email and phone number.

## Footer Section:

- Contains closing content or additional information.
- In this case, it simply thanks visitors for visiting the webpage.

## Images and Figures:

- Throughout the document, there are images used to visually represent sections. These are enclosed within `<figure>` tags.

## Styling:

- External CSS file linked in the head section (`style.css`) is referenced to apply styles to the HTML elements.

Overall, the structure follows standard HTML conventions with clear separation of content and presentation. Each section is logically organized and labeled using appropriate HTML elements.

# CSS Styling Overview

This README provides an overview of the styling applied to various sections of a webpage using CSS.

## Header Styling (`header`):

- Utilizes flexbox to arrange its children in a row with space between.
- Sets a background image that covers the header, with a fallback background color.
- Defines text color, padding, and font family.

## Navigation Styling (`.nav nav`):

- Uses flexbox to distribute navigation links evenly.
- Applies background color, font family, font weight, color, font size, and removes text decoration from navigation links.
- Adds a hover effect on navigation links.

## About Me Section Styling (`.about-me`):

- Applies flexbox to the container and defines font family and font size.
- Aligns the figure (image) to the center and sets its color.
- Adds a left border, padding, and margins to the text content.

## Work Experience Section Styling (`.work`):

- Similar to the about me section, but with adjustments in margin-top and margin-bottom.

## Projects Section Styling (`.projects`):

- Similar to the about me section, with adjustments in margin-top and margin-bottom.

## Contacts Section Styling (`.contacts`):

- Utilizes flexbox for layout.
- Aligns items in the figure to the center, sets color, and defines font family and font size for the text content.
- Adds a left border, padding, and margins.

## Footer Styling (`footer`):

- Utilizes flexbox to center its content.
- Sets background color, text color, and font family.

## Media Queries for Responsive Design:

- Adjusts the header background image when the viewport width is less than or equal to 1700px.
- Shrinks all `<img>` elements within various sections when the viewport width is less than or equal to 1400px.
- Stacks all sections in a column layout when the viewport width is less than or equal to 1280px, except for the navigation bar.

## Author

- [@MarcioPimentel01](https://www.github.com/MarcioPimentel01)

