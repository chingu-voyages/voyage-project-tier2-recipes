# voyage-project-tier2-recipe

## Table of Contents

* [Overview](#overview)
* [General Instructions](#general-instructions)
* [Requirements & Specifications](#requirements-specifications)
* [Acknowledgements](#acknowledgements)
* [About Chingu](#about-chingu)

## Overview

Ingredients and recipes are fundamental components of the culinary world, 
working together to create a wide array of dishes and flavors. 

Ingredients are the raw materials used in cooking and food preparation while 
Recipes are sets of instructions that outline how to prepare a specific dish.

They detail the ingredients, their quantities, and a step-by-step process to 
create the desired culinary outcome.

![Ingredients And Recipe](./assets/ingredients-and-recipe.jpg)

Your Chingu Voyage team will be using this data to create an app that will help 
anyone interested in creating dishes and flavours to explore this recipe in novel ways. 
Your app will summarize this data and will allow users to select subsets of it for 
detailed step-by-step process.

This will provide you with an opportunity to build Web Development experience
dealing with large volumes of recipe data, nutritional information with a subset of
categories, and user queries.

## General Instructions

This project is designed to be worked on by a team rather than an individual
Chingu. This means you and your team will need to thoroughly read and
understand the requirements and specifications below, **_and_** define and
manage your project following the _Agile Methodology_ defined in the
[Voyage Handbook](https://chingucohorts.notion.site/Voyage-Guide-1e528dcbf1d241c9a93b4627f6f1c809).

As you create this project make sure it meets all of the requirements, but once
it reaches MVP, start implementing the optional features or get creative and
extend it in ways we haven't envisioned. In other words, use the power of
teamwork to make it distinctive and unique.

Take note that we haven't given specific direction on what your UI/UX should
look like. This is another area where you and your team can put your creativity 
to work! 

## Requirements & Specifications

### What You Need to Do

The following define the minimum requirements and ideas for features you may
implement to enhance this app, if time permits.

#### Structure

- [ ] This is a purely frontend application. No backend is required. 
- [ ] You may use any languages, tools, or libraries you prefer when designing and building this app. 
- [ ] You should leverage the [Recipe - Rapid API](https://tasty.p.rapidapi.com/recipes/list) as a recipe resource.
- [ ] You may **_NOT_** use AI-base solution generators like GitHub CoPilot.
- [ ] Useful links and resources:
    - [Example Recipe App](https://namka-food-api.netlify.app)
    - [Recipe - Rapid API](https://tasty.p.rapidapi.com/recipes/list)

#### Styling

- [ ] Surprise us!!! Use your teams creativity to make this app distinctive.
- [ ] Add a footer containing a link to your teams GitHub repo
- [ ] In general, you will find these [UI design principles](https://www.justinmind.com/ui-design/principles) helpful.
- [ ] Recommend using this resource for [clean CSS](https://www.devbridge.com/articles/implementing-clean-css-bem-method/)

#### Functionality

-   User can see a landing page containing at least the following components:
    - [ ] Header component displaying a welcome message.
    - [ ] Search field that enables users to input ingredient(s).
    - [ ] A component to explain the use of the application.
    - [ ] A scrollable list of recipes displaying the results based on the search criteria.
    - [ ] A summary main recipe component: it should display recipe image, name and link to details.
    - [ ] A summary detail recipe component: it should display recipe name, category, and instructions.
    - [ ] Ensure mobile responsiveness for the application.

- Search Component
    - [ ] Users can input one or multiple ingredient(s).
    - [ ] Initiate the search by either pressing the Enter key or clicking the 'Search' button/icon.
    - [ ] Display an error message when an unlisted item is entered.

- Main Data Display Component
    - [ ] Display result for each recipe in the main component.
    - [ ] Remain on the landing page if no search ingredient has been entered.

- Summary Detail Component
    - [ ] Display the following information of the selected recipe:
        - Name
        - Category
        - List of instruction
        - List of nutrition
    - [ ] Add a Link to the instruction video
    
### Extras (Not Required)

-   Search Component
    - [ ] Enable the preservation of search criteria between sessions, allowing users to select them from a dropdown menu when needed.
-   Detail Data Display Component
    - [ ] List of ingredient
-   Summary Metrics Component
    - [ ] Incorporate pagination for organizing the collection of recipe search results.
-   General
    - [ ] Support dark/light mode
    - [ ] Allow the user options for customizing the font and font size

## Acknowledgements

Data is been pulled from [Tasty of Rapid API](https://tasty.p.rapidapi.com/recipes/list). 

## About Chingu

If you aren’t yet a member of Chingu we invite you to join us. We help our 
members transform what they’ve learned in courses & tutorials into the 
practical experience employers need and want.