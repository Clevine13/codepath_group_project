Unit 8: Group Milestone - README
===


:::

# News App 

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)

## Overview
### Description
Tracks what music an individual listens to, and pairs them with others based on that music. Could be potentially used as a dating app, or just meeting new friends with similar music tastes.

### App Evaluation
- **Category:** Educational / News
- **Mobile:** This app would be primarily developed for mobile but would perhaps be just as viable on a computer, such as CNN or other similar apps. Functionality wouldn't be limited to mobile devices, however mobile version could potentially have more features.
- **Story:** Takes in current news from and API database, and shows the user their desired news based on the selection of categories. The user can then decide which news articles they want to read or skip.
- **Market:** Any individual could choose to use this app,Especially given the range of topics listed on the app.
- **Habit:** This app could be used as often or unoften as the user wants. It honestly depends on how often they want to be informed about a certain topic or not day to day.
- **Scope:** First we would start with the creation of the base hme page for the app then perhaps this could evolve into a application where the user can share or save specified articles. Large potential for use other publishing news applications to use.

## Product Spec
### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* App Must Display Multiple areas of research 
* Must must have the option to vies entire article
* App article must display images related to the specified topic
* Mutiple stories or articles per section
* App must route to correct destination news topic.

**Optional Nice-to-have Stories**

* Log of past news articles views
* Page of most views articles
* Profile Add-On: Top music choices, etc.
* Optional Shuffle Button (i.e. random encounter/random song)
* Listening/Encounter Queue

### 2. Screen Archetypes

   * Upon Download/Reopening of the application, the user is taken to the home page of the news app 
   * ...
* Home Screen
* This area shows all the avalable areas of news that can be viewed by the user.
* Article Screen 
   * Allows user to view the specified article that they have selected
* Full Article Screen.
* Allows the user to navigate to the full page/area of the specified article

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Technology
* Sports 
* Science
* Health

Optional:
* Profile to save data and interest 
* Discover (Top Choices)
* Beauty section 
* Life section
* Politics sections 
Wire Frame Image: (https://user-images.githubusercontent.com/43858669/162976626-900fec12-c8bc-4748-956a-a92d41f8c38d.png)

Models:
Post
Property	Type	Description
objectId	String	unique id for the news sections
author	Pointer to news author
image	File	image that is used for news posts
headline	String	newsa headline by author
createdAt	DateTime	date when post is created (default field)
updatedAt	DateTime	date when post is last updated (default field)

Networking:

List of network requests by screen
Home Feed Screen
(Read) Read in all the news data from news api endpoint 
Selected Article Screen
(Read) Get the extended contents of the selected news article for the user
Full News Post Screen
(Read) Get the Full dedicated news article from the api data for the user to read. 


