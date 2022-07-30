## hoori.

**table of contents**

## Table of contents
1. [Introduction](#Introduction)
2. [Start](#Start)
3. [Functionality](#Functionality)
    1. [User Stories](#User-Stories)
    2. [Issues](#Issues)
    3. [Functionality: Design](#Functionality:-Design)
4. [Design](#Design)
    1. [Wireframes](#Wireframes)
    2. [Database](#Database)
    3. [Fonts](#Fonts)
    4. [Logotype](#Logotypes)
    5. [Icons](#Icons) 

5. [Issues](#Issues)
6. [Testing](#Testing)
    1. [Validators](#Validators)
    2. [User Stories](#User-story-testing)
    3. [Feature Testing](#Feature-tests)
    4. [Bugs](#Bugs)






## Introduction

This project is named "Hoori" which refers to the japanese god Hoori who was the god of grain and rice. The reason for this is that the site will collect recipes with the intent to break them down to their core which is the reason that the macros are included. Further, it will give a helping hand in the style direction of the user interface, that will aim to be sleek and minimalistic. 

## Start

## Functionality

### User Stories

Users should be able to register

https://github.com/redbasel/wellness_recipes_p4/issues?q=is%3Aissue+is%3Aopen+label%3A%22User+story%22

### Wireframes

## Issues

(links to label issues.)

### Functionality: Design

### Wireframes

### Fonts

### Colortheme

### Logotype

The logo is based on the "Helvetica" font in bold, all lowercaps letters with a dot in the end in an attempt to keep the logo sleek and easy. 

### Icons

Upgraded FontAwesome to the latest version 6.1.1 from 5.14 in order to be able to utilize the wheat icon. 


## Issues

https://github.com/redbasel/wellness_recipes_p4/issues?q=is%3Aissue+is%3Aopen+label%3Aissue

## Testing

Below is a summary of the tesing done.
    1. [Validators](#Validators)
    2. [User Stories](#User-story-testing)
    3. [Feature Testing](#Feature-tests)
    4. [Bugs](#Bugs)

### Validators

html - w3c
css - jigsaw
javascript - jshint
python - PEP8
lighthouse maybe



### User story testing

Write my user stories and how they are adresssed



### Feature tests

Check that all buttons and links works and act as intended to. 

#### Navbar

The navbar has a couple of buttons and properties which need to be tested that they direct the user to the correct place but also that they shift property based on the status of the user i.e if they are a visitor or logged in user. 

##### As a visitor

"home" when pressed should take you to the starting page. 

"register" when pressed should take you to the signup page.

"login" when pressed should take you to the sign in page.

The user "status" should say "user:visitor" when not logged in.


##### As a logged in user

"home" when pressed should take you to the starting page. 

"register" should have changed to "logout" and when pressed should take you to the "signout" page, asking if you are sure.

"log in" should have changed to "add a recipe" and when pressed should take you to the "add recipe" form where you will fill out all details regarding the recipe. 

The user "status" should say "user:'username'" when not logged in. 'username' is a placeholder for the name of the logged in user. 

#### Homepage

The hero has variable elements based on whether the visitor is a logged in user or just a visitor.

##### Hero as a logged in user




### Bugs




