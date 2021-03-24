# DGL-114-ProcessPortfolio


## Week-1

### 0101

![image of netflix app](https://o.aolcdn.com/images/dims?thumbnail=640%2C&quality=95&image_uri=https%3A%2F%2Fs.yimg.com%2Fuu%2Fapi%2Fres%2F1.2%2FoVMZ2gvB1LzRIoOvyoxPXQ--%7EB%2FaD01Mzk7dz04MTQ7YXBwaWQ9eXRhY2h5b24-%2Fhttps%3A%2F%2Fo.aolcdn.com%2Fhss%2Fstorage%2Fmidas%2F4bbe729373c68407aa49de24f8a402a7%2F206192931%2Fnetflixpreviewslede.png&client=amp-blogside-v2&signature=6fc8a0dc46ec1fb84d595ec76099511a941d5b21)
<p>I like the netfix mobile app's interface.The best part about it is the simplicity involved in it. I like how the user can constantly navigate throught the search page, the home page, download page as well as the more page. The color combination used by them is quite good and isn't rough on the eye</p>

![image of facebook app](https://cdn57.androidauthority.net/wp-content/uploads/2017/06/android-authority-facebook-watch-update-22.jpg)
<p>The other app example would be the Facebook app. It's not that I hate it or dislike it,its just that it takes a while in order to get to know it better. I reckon there are quite a lot of features in it, but they just aren't quite presentable. As a user at times I used to get confused from where to upload a photo.Should it be using the camera button or the posts feature?And getting the same content on the feed at times bores me and makes me shut down the app</p>

### 0102

<p>The following are things in an app that I consider to be intutive which also makes them usable</p>

- Good Speed
  - I like it when I don't have to wait for it to load content
- Privacy/Security
  - Giving acess to someone's data is very personal.When I give mine to an app, I expect confidentiality and discretion would be provided
- Color contrast
  - I would look at the Netflix home page for hours looking for a Movie than on facebook, simply because the colors used by Netflix is less painful to eyes
- Notification
  - I like it when Facebook provides me with notifications about my friend's birthday or at the event of someone liking/commenting on my post. It keeps the user informed

## Week-2

### 0201

<p>The app that I use frequently is Snapchat and its <strong>features</strong> are as follows:- </p>

- location
- speakers 
- microphone
- camera
- touchscreen
- multitouch

<strong>permission :</strong> 
- Camera
- Microphone
- Notifications 
- Storage
- Contact

### 0202

<p>The app that I use frequently is Snapchat</p>
<p>I will be identifing the MVC pattern in its friends page</p>
<img src = "snapchat.png" alt= "snapchat screenshot" height = 300/>

<p>The <strong>Model</strong> is as follows </p>

- The user icon at the top left 
- The users friends 
- The image of each user
- The groups that the user is part of

<p>The <strong>View</strong> is as follows </p>

- Displaying each users activity 
- Ensuring that the images are at the left 
- The buttons at the bottom to change page

<p>The <strong>Controller</strong> is as follows </p>

- Updating the user's friends' snaps
- Notifying the user if the receive a message
- Disabling the snap once viewed

## Week-3

### 0301

<p>The app that I chosse is facebook.The activities in it are as follows:</p>
  
  -  Camera
  -  Feed
  -  Search
  -  Messenger
  -  notifications 
  -  Marketplace

<p>The app contains these features mainly in the header</p>

### 0302

<p>Facebook uses the following events</p>

  -  onClick
    -  Clicking a profile to open it
    -  Clicking the like button to like a post
    -  Clicking on the header images to follow other activities 
    
  -  onLongPress
    -  Long pressing the like button would give other ways to react to a post
    
  -  onDoubleTap
    - double tapping an image zooms in the image

## Week-4

### 0401

App choosen Snapchat

<p>I reckon snapchat is an app that has a flat structure. The top bar and bottom bar both provide different views and activities. The friends section of the app provides insight to the messages, which as well is a flat structure. The setting however shows some signs of hierarchy. It's an activity that provides the path to navigate towards different navigations</p>

## 0403

<p>After reading the provided resourses I feel that a top bar can be used without any actions, whereas a bottom bar is much prefered when we are dealing with multiple screens. The bottom bar in snapchat has multiple actions like moving to photos view or friends view. It is common to have a Floating Action Button (FAB) on a bottom bar.</p>
<p>There are certain differences when it comes to principles that govern the top and bottom bars: Top bars lean towards the principles of Persistent, Guiding, and Consistent, whereas the bottom bar leans towards Actionable, Flexible, and Ergonomic</p>

## Week-5

### 0502

App choosen WhatsApp

| gestures      | Event |
| ----------- | ----------- |
| Tap      | Its responsible for the majority of the UI work, like opening a particular message or settings |
| Long Press| Its responsible for providing additional options for each message, such as archive, delete and mute |
| Scroll | Its used to scroll through each content |
| Fling | Its used to go throug the messages fastser |

### 0503

<p>We are to use dialogue to grab the user's attention towards a particual peice of task or information</p>
Dialogue can be divided as follows: 

-  Alert Dialogue:
    -  This type of dialogut interrupts the user from the task they are currently doing. 
    -  It should be used only if the task/information is extremely important
-  Simple Dialogs
    -  It is used to provide information to the user about what is to happen next if the user proceeds forward
-  Confirmation Dialogs
   - It should primarily be used as the decision taking dialog
   - They are a bit similar to radio buttons in terms of usage
-  Full Screen Dialogs
    - It should be used as a todo task manager
    - It should use keyboard as an input sourse
    - It has the power to display another dialog in itself


## Week-8

### 0801

App choosen Instagram
-  Shared Preferences:
    -  Which stories were vied, which messages were read and replied, the user's stories, the user's bio.
-  App-Specific Files:
    -  The user's chat with other users, like and comments option are App-Specific Files. 
    -  The Posts could also be considered as App-Specific Files	
-  Shared Storage:
    -  Most of the files seem to be stored on the cloud. But the app gives the user permission to store some to their files on local storage, provided they are logged in and are storing data regarding their own profile.
-  Database:
    -  Mostly all the files are uploaded to the cloud and not the user's disk. Thereby I gather that Instagram rarely uses local database. Something like the users login details could be stored in the disk storage
-  Cloud:
    -  Mostly all the files are uploaded to the cloud and not the user's disk. Thereby I gather that Instagram mostly uses cloud based database. Something like the users posts could be stored on the cloud.

### 0802

Advanced To-Do list settings
-  Shared Preferences:
    -  The user's prefered theme. Tasks completed or incomplete.
-  App-Specific Files:
    -  At times the user might want to store extremely private information, so maybe the app could use encryption to do so.
-  Shared Storage:
    -  If the user uploads images, videos or any documents then maybe that could be used by other apps.
    -  If the user wishes to post their list on social media, then we could do so by using shared storage
-  Database:
    -  The user could synchronise their to-do list items with a clock/calender locally.
-  Cloud:
    -  If the user wishes to run the app on multiple devices then we can make that happen by using cloud storage

## Week-9

### 0901

Room is a way to implement SQLite. Its primary principle is to make operations that use database easy for the developer.Room consists of 3 components
-  Database Class:
    -  It holds the database and allows us to access it
-  Entities:
    -  They are tables within our Database
-  Data Access Objects(DOA):
    -  It provides methods so as to allow us to update the database 

### 0903

Improvements that needed to be made in Study Helper App
-  The app should hold design according the users preferred theme.
-  The card should inform the user which question is it that they get wrong the most and should push that so the user could revise it
-  Add a clock to remind the user to study
-  Add an inapp timer to implement the Pomodoro study technique

## Week-10

### 1002

-  Display of Notifications:
    -  We need to consider the users privacy while displaying the notification on either the lock screen or on the home screen. If there are messages from another user, the user should just get a notification that states that they've got a new message. Any information related to the message or the message sender should not be posted on the notification.     
-  Notification actions:
    -  Depending upon the reason behind the notification, we could give the user options to interact with the notification. For instance if an alarm clock notification comes up, the user should be provided options to either snooze or maybe close the alarm. 
-  Display propertis of Notifications:
    -  Depending upon the users preference theme, the notification should be presented.

### 1003

The app shoud not be sending user notifications if:
 -  The app has to advertise something not releated to the app
 -  The user has never opened the app
 -  The purpose of the notification is to ask the user to rate the app
