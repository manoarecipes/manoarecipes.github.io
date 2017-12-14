---
title: Manoa Recipes
<a href="https://github.com/manoarecipes">View on GitHub</a>
---


# Table of contents

* [About Manoa Recipes](#about-manoa-recipes)
  * [Installation](#installation)
  * [Goals](#goals)
* [Development History](#development-history)
  * [Week 1:Website Development](#week-1-website-development)
  * [Milestone 1: Mockups and Collections](#milestone-1-mockups-and-collections)
  * [Milestone 2: Connecting the Data](#milestone-2-connecting-the-data)
* [Deployment to Galaxy](#deployment-to-galaxy)

# About Manoa Recipes

Manoa Recipes is a Meteor application providing recipes for the University of Hawaii community. In the application, users can search recipes by ingredient, add recipes to the database, save recipes to their profile, and view local grocery ads.

When the site is first accessed, even before they log in, users may filter through ingredients to view recipes that fit their cravings:

As a non-logged-in guest, users may still access several application features, including the recipe database and the weekly ads. Manoa Recipes utilizes UH Manoa's Central Authentication System (CAS) to allow access to those with UH login credentials:


Once logged in, the user is taken to their profile page, which at first will be mostly empty:


The user can update their profile to better represent themselves:


They can browse through the entire database of recipes:


Once logged in, users can favorite recipes by clicking the star on any card. These recipes will appear on their profile page:

Clicking on the recipe photo will bring the user to the recipe's display page:

Users can also populate the database with their own recipes:

Once the recipes are in the system, they will appear on the user's profile page, and may be edited or deleted only by those users:


Or they can access the weekly ads, which will be updated weekly by our admins:

# Installation

First, [install Meteor](https://www.meteor.com/install).

Second, [download a copy of Manoa Recipes](https://github.com/manoarecipes/manoarecipes/archive/master.zip), or [clone it using git](x-github-client://openRepo/https://github.com/manoarecipes/manoarecipes).
  
Third, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000). If you have an account on the UH test CAS server, you can login.  


## Goals

The goal of this project is to develop an application for users and the public to share recipes. The public will be able to browse recipes by category or tag. Users will be able to log in, create a profile, create recipes, and save recipes for future reference. Other features can be implemented but the aforementioned are the basics.

# Development History

This project is a work-in-progress.

The following sections document the history of Manoa Recipes.

## Week 1: Website Development

We created a Github organization to host our code and attached our website repository. As a group, we decided the basic functionality of our application and developed the following mockups:

<img src="images/landing-page.png"/>
<img src="images/recipe-profile.png"/>
<img src="images/recipe-directory.png"/>
<img src="images/create-recipe.png"/>

## Milestone 1: Mockups and Collections

This milestone started on November 10, 2017 and ended on November 22, 2017

The goal of Milestone 1 was to create mockups of the core pages of the project, and if there was time, to start working on creating the collections.

Mockups for the following five pages were implemented during M1:


[<img src="images/LandingPage.png"/>](http://manoarecipes.meteorapp.com/)

[<img src="images/ProfilePage.png"/>](http://manoarecipes.meteorapp.com/mserai/profile)

[<img src="images/EditProfile.png"/>](http://manoarecipes.meteorapp.com/mserai/edit-profile)

[<img src="images/RecipeDirectory.png"/>](http://manoarecipes.meteorapp.com/mserai/recipe-directory)

[<img src="images/AddRecipe.png"/>](http://manoarecipes.meteorapp.com/mserai/add-recipe)



Milestone 1 was implemented as [Manoa Recipes Milestone M1](https://github.com/manoarecipes/manoarecipes/milestone/1)::
![](images/M1-ThreeColumn.png)

Milestone 1 was implemented through Issue Driven Project Management [Manoa Recipes Network Graph](https://github.com/manoarecipes/manoarecipes/network):: ![](images/Graph.png)

## Milestone 2: Connecting the data

This milestone started on November 22, 2017

Milestone 2 is being implemented as [Manoa Recipes Milestone M2](https://github.com/manoarecipes/manoarecipes/milestone/2)

# Deployment to Galaxy
The project was deployed through Galaxy and [may be found here](https://manoarecipes.meteorapp.com):: ![](images/Deployment.png)
