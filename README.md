## Description

This is a Portfolio Website built using HTML and SCSS displaying projects and experience. The goal of the project was to use technologies such as SCSS which I had been learning as well as implement modern design approaches such as responsive design.

## Setup
Clone this repository and open the index.html file.

Alternatively hosted [here](https://robertos-portfolio-site.netlify.app)

## Approach  

I chose to use SCSS over vanilla CSS as it allows me to improve maintainability, readability and modularity with the additions of nested syntax, variables. I used nested syntax to prevent having to rewrite selectors multiple times whilst providing better code organisation and structure to the code, aiding the maintainability. I used variables to define values for colours and fonts which I was using in multiple places on the site, allowing me to change it in one place only aiding in maintainability.       

## Struggles

One of the main challenges that I encountered was implementing responsive design, automatically adjusting the design of the site for different devices. This lead to extensive research into CSS media queries, which allows you to target different media states as the design is rendered on a device. I used media queries to adjust the design such as the number of columns in a table or the width of certain divs depending on the width of the display. I used SCSS mixins to define the media queries and reuse them across the website to aid maintainability.

## Things I would do differently

If I were to change anything, I would recreate the website in React to generate components dynamically such as the list of projects and skills, and to retrieve them from a database so that I could easily update the website without having to alter the design. Currently, when I add a new project to the project section, I have to change the amount of columns and rows in the table manually, generating the components dynamically would solve this issue. 

