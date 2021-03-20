#  **BONSAI STARTING GUIDE WEBSITE** 

The goal of the project is to provide users some introduction to Bonsai art, including instructions of how to grow one from seed.

This is my first milestone project, providing easy navigation across multiple sites, simple esthetics, and basic information users look for.

[Live site - Bonsai](https://dinkokmonicek.github.io/Milestone-Project-1/)

## **Table of Content**

- [User Experiance](#user-experiance)

- [Technologies Used](#technologies-used)

- [Testing](#testing)

- [Deployment](#deployment)

- [Credits](#credits)

- [HTML Walkthrough](#html-walkthrough)


## **User Experiance**

- This website is for anyone looking for some beginner information about Bonsai trees.

- Home page provides minimum content, as well as some interestings facts.

- Grow page provides information about how to grow Bonsai tree from seed, and where to get them, locally in Dublin, and online on Amazon.


## **Technologies Used**

- Languages
    -   [HTML5](https://en.wikipedia.org/wiki/HTML5)
    -   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)  
            - CSS linked to a separate style.css file

- Other resources and tools
    -   [Google Fonts](https://fonts.google.com/)  
                - "Roboto", sans-serif;

    -   [Font Awesome](https://fontawesome.com/)  
                - Icon used in navbar-background

    -   [Bootstrap 5](https://getbootstrap.com/)  
                - Site is using bootstraps content delivery network  
                - Bootstraps navbar used across all sites  
                - Various tools used for containers, rows, and cols

    -   Various google images used for a project  
            - **THIS SITE IS ONLY A PROJECT, AND WILL NOT BE USED FOR ANY OTHER PURPOSE BESIDES CODE INSTITUTE MILESTONE PROJECT**

## **Testing**

- Site has been tested across all screen sizes
- Responsiveness made manually with mediaQueries

## **Deployment**

- Live site has been deployed on [GitHub Pages](https://dinkokmonicek.github.io/Milestone-Project-1/)

## **Credits**

- [Bonsai Empire](https://www.bonsaiempire.com/)  
            - Various text sourced from here
- [Bonsai And Blooms](https://www.bonsai-and-blooms.com/growing-bonsai-from-seed.html)  
            - Growing information sourced from here  
            - This site referenced as a button below growing information
- Images found at google used on site  
            - **THIS SITE IS ONLY A PROJECT, AND WILL NOT BE USED FOR ANY OTHER PURPOSE BESIDES CODE INSTITUTE MILESTONE PROJECT**


## **HTML Walkthrough**

### ***SHARED ACROSS ALL SITES***
- ##### NAVBAR
    - Created using bootstrap
    - Just one responsive change with navbar items being a collapse list when viewing on a screen < 992px

- ##### FOOTER
    - Two responsive columns made using bootstrap
    - When > 992px they become inline-blocks



### ***INDEX.html***

- Index has two sections, displayed one below the other
- All sections made using bootstraps row/cols

- ##### FIRST SECTION

    - Background classed bonsaiBackground
    - First impression background with some text displayed in upper and lower text blocks  
                text blocks classes - bonsaiContent and bonsaiContentSecond
            

- ##### SECOND SECTION

    - Some interesting info about theme of the site
    - Breakpoints at 992px, when < displayed as blocks, when > displayed as inline blocks
    - Background classed bonsai2Background
    - Two divs regarding content are classed bonsaiSection and definitionSection



### ***GROW.html***

- Information about growing your own bonsai.
- Made up of summaries and details for easier overview.

- Seeding information referenced from [Bonsai And Blooms](https://www.bonsai-and-blooms.com/growing-bonsai-from-seed.html)
    - Source link reference added on the bottom of the grow.html


### ***CONTACT.html***

- contactDiv with contact information placed inside contactBackground div
- contactDiv breakpoints made using css's media queries, editing only div's width on each breakpoint
