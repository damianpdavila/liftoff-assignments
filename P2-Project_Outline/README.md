# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
Car Pool Match is like a dating app for car pooling.  Sharing rides is obviously good for the environment, for your wallet, and may even help you expand your social life.  But how do you find the perfect match??

Car Pool Match allows users to specify their "match" criteria, and then it will try to find their perfect match.  Criteria like:
* distance from drop off/pick up location
* time to leave
* drop only/ pick up only/ both/ none (rider only)
* smoking preference, etc.

The app will rank the matches and suggest them to the user.  A map will be used to help visualize the locations of the potential car pool matches. 

The idea came from personal frustration over car pooling to my daughters' school.

### Features
**User Login:** Users will be able to create accounts and log in to the application. Each user will have a profile page.  Users will specify their match criteria/preferences in their profile.

**Match:** Match will be based on weighted criteria.  The match will occur whenever user updates their match criteria. Matched profiles will be displayed in textual list and also as pins on a map: "good" pins for strong matches, and "bad" pins for profiles that are not a good match.  User will be able to contact the matched profile via email through the app, without direct access to the matched profile's email (for privacy reasons).

**Broadcast:** Notify all users when a new person registers, to help all users get matched (or find a better match).

### Technologies
* Java
* Spring Boot framework
* Thymeleaf templating
* Java Persistence API / Hibernate ORM
* MySQL
* Google Maps API
* Javascript
* Spring Security (probably, or something like it)
* Bootstrap (probably)

### What I'll Have to Learn
I must learn "real" user registration and authentication practices in Java.

I must figure out how the profile match will work.  Some criteria are simple (smoker/non-smoker) but many will be difficult to model in database and to match against.  For example: drop only/pick up only/both/none (rider only)

I must learn how to use the latest Google Maps API to calculate distances between points and also to display locations on a map.

I would like to learn how to create an API so that the profile matching process can be more dynamic, and not based on a full page send.

I would like to find an easy way to create something better than "vanilla" Bootstrap UI.

### Project Tracker
I plan to use Trello, but if there's time I will investigate Asana.
