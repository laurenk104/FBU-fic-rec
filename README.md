Original App Design Project - README Template
===

# APP_NAME_HERE

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Recommends fanfics based on the user's preferences.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Matching (and Social)
- **Mobile:** While the matching aspect could easily be done on the web, the mobile aspect helps emphasize the social media aspect of ao3, propoting people to like or comment more frequently.
- **Story:** Allows users to find fics that are tailored to them, and they are more likely to read.
- **Market:** Fandoms
- **Habit:** Creates a more personalized reading experience that encourages users to return.
- **Scope:** V1 would provide recommendations organized by fandom and genre. V2 would implement more ao3 functionality, like reading and interacting with the fic.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can login
* User can create new account
* User can change their profile picture
* User can see an overview of recommendations based on the user's profile as a whole

**Optional Nice-to-have Stories**

* User can organize recs by fandom and genre
* User can modify more of their profile settings
* User can interact with published fics
    * User can read fic directly in the app
    * User can kudos/comment/bookmark

### 2. Screen Archetypes

* Login Screen
   * User can login
* Registration Screen
   * User can create a new (ao3) account
* Stream (home feed)
    * User can view their top recommendations
    * User can organize this stream by fandom and genre
* User Settings
    * User can make changes to their account (like adding a profile picture)
* Detail view
    * User can view details about the fic

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Feed
* User Settings

**Flow Navigation** (Screen to Screen)

* Login/registration
   => Home
* Home Feed
   => Detail view
* User Settings
   => None
* Detail view
   => Home

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
