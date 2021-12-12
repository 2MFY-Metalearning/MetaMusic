README
===

# Meta_Music 

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Tracks what music an individual listens to, and pairs them with others based on that music. We can meet new friends with similar music tastes. In addition, people can check the latest concert information.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Entertainment, Networking
- **Mobile:** iOS, Android, our app would be primarily developed for mobile.
- **Story:** Help users to share and listen to music in a fun and easy way. At the same time, users can connect with others with the same interest and make friends.
- **Market:** People who prefer to use our App, want to connect with others and check out the latest music information.
- **Habit:** How often the App is depend on the users.
- **Scope:** Pairing people with similiar music taste, perhaps this might become a music sharing application. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Users register to new account (Email, Facebook)
* Users logs in to access account
* User picks what their favorite artist/genre/etc.
* Settings (Accessibility, Notification, General, etc.)
* User can check the lastest music concert information.

**Optional Nice-to-have Stories**

* Log of past songs/people with album art covers matching
* Page of most use learning material (i.e. learning material that most users are connecting through)
* Listening/Encounter Queue


### 2. Screen Archetypes
* Login 
* Register - User signs up or logs into their account
   * Upon Download/Reopening of the application, the user is prompted to log in to gain access to their profile information to be properly matched with the learning Material and connect between group. 
* Profile Screen 
   * Allows user to upload a photo and fill in information that is interesting to them and others
* Song Selection Screen.
   * Allows user to be able to choose their desired subject, class, genre of preference and begin learning and interacting with others.
* Settings Screen
   * Lets people change language, and app notification settings.
* Search Screen
   * people can search the latest music concert information

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* log in/ out screen
* Search event
* Profile
* Settings

Optional:
* Discover (Top Choices)

**Flow Navigation** (Screen to Screen)

* Forced Log-in -> Account creation if no log in is available
* Learning Selection (Or Queue if Optional) -> Jumps to Chat/ FAQ's
* Profile -> Text field to be modified. 
* Settings -> Toggle settings

## Wireframes
<img src="https://i.imgur.com/uixkk6P.jpg" width=800><br>

## Schema 
[This section will be completed in Unit 9]
   | Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | objectId      | String   | unique id for the user post (default field) |
   | author        | Pointer to User| image author |
   | image         | File     | image that user posts |
   | caption       | String   | image caption by author |
   | likesCount    | Number   | number of likes for the post |
   | createdAt     | DateTime | date when post is created (default field) |
   | updatedAt     | DateTime | date when post is last updated (default field) |
   | monthlyevents | DateTieme | date every friday| 
### Models
[Add table of models]
### Networking
-Home Feed Screen
  - (Read/Get) Query all posts where user is author
  - (Create/POS) create a new like on a post 



  - (Delete) Delete existing like

-Create Event Screen
  - (Create/Event) Create a new event object

-Profile Screen
 - (Read/GET) Query logged in user object
- (Update/PUT) Update user profile image

Progress So Far - Sprint 1
* Users register to new account e.g. E-mail
* Users logs in to access account


### login
<img src='https://media.giphy.com/media/oXv1sFtZKZHBcCtUfZ/giphy.gif' width= 250> <br>
