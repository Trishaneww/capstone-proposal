# capstone-proposal

# Project Title

## Overview

Flashcard memory studying application

### Problem

Users can store study notes in an organized and consise format. They can then quiz themselves using the flashcards/studydecks they create

### User Profile

Target audience are students who need to create various studydecks (different classes etc)

### Features

- Users can create and delete studydecks
- Users can create and delete flashcards, contained within a studydeck
- Users can create an acount
- Uers cann view other uers public studydeks
- Uers can collaborate and create flashcards for a selected studydeck
  

## Implementation

### Tech Stack

- React
- Mysql
- Knex
- sass

### APIs

List any external sources of data that will be used in your app.

### Sitemap

Homepage
- Users can view public studydecks, aswell as their own page
- Fixed navbar to direct users to other pages

Login/Signup Page
- Uers can login or create an account

Deckpage
- Dynamic page for each studydeck and its contents


### Mockups


### Data

3 TABLES
users - decks - flashcards

the decks table will reference the users table
the flashcards table will reference the decks table

### Endpoints
get request -> get all studydecks and flashcards
put request -> creates flashcard or deck
patch request -> update details of a flashcard, studydeck, or username. Can also toggle whether a deck is made public or not
delete request -> delete studydeck or flashcard

### Auth



## Roadmap


## Nice-to-haves


