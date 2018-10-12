# Disaster-Assistant
An android application to help people communicate with each other and provide services to them during disasters.

# Introduction
This is an android application which will provide users with facilities that will improve their chances of survival during a calamity. Basic features of this app will be:
1. An SOS button which immediately shares the user's location with nearby people using the app and the authorities.
2. Direct communication with rescue team deployed by the government.
3. A list of emergency numbers.
4. Information/news about services provided by the government and provide their links.
5. Tips/Do's and Dont's about calamities.
6. List of nearby safe places and their routes.
7. Constant updates about calamity occurrences in nearby regions.

# Features
The app will have two modes: Normal Mode and Emergency Mode.
Points 1 and 7 are explained here:
1. The SOS button: This button is the most important feature of our app. It does four tasks:
a. Switches to the Emergency Mode. All subsequent steps are repeated in every 5 minutes.
b. Sends the location of user alongwith a distress signal to all the concerned authorities and displays their phone numbers for the user to contact them directly.
c. Broadcasts the user's location to all other users of the app within a 5 km radius.
d. Sends a distress message and location to all the personal contacts provided by the user even if they don't use the app.
2. During a calamity, app is switched to Emergency Mode by pressing SOS button and a notification will be sent to all users in the non-affected neighbourhood regions, warning them about the calamity.

# Mode of Communication
1. Location is retrieved using GPS.
2. In absence of internet, location is sent as text message (address and coordinates are sent).
3. Necessary areas of map are downloaded beforehand and made available offline.
4. Cellular network is used in absence of internet for communication with people.

# Case of Misuse
Misuse of SOS button will be treated as decided by authorities. 

We will consider ourselves successful if we are able to save even a single life.
