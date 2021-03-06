---
layout: project
type: project
image: billmullen42.github.io/images/letumgrowlogo.jpg
title: LetUmGrow
permalink: projects/LetUmGrow
date: 2016-12-14
labels:
  - Web app
  - Javascript
  - HTML
  - Meteor framework
  - Hawaiian plants
summary: My team created a web application to help UH Manoa students document and care for the plants in their area.
---

<img class="ui large centered rounded image" src="/images/Species Database.png">

[LetUmGrow Landing Page](https://letumgrow.github.io/).

LetUmGrow is a web application for those interested in discovering and caring for the amazing variety of plants found in the Manoa Valley, near the UH Manoa campus. A map of the local area allows users to add profiles on specific plants and their locations, and easily return to the same location. Plant profiles link to species information in our database, using data provided by the UH Landscaping Department. The app includes secure login and user functionality, and was built using the Meteor framework, JavaScript, and HTML.

I contributed the User Profile functionality and much of the Mongo DB functionality for this project, setting up Collections and Schemas for user profiles, contacts, and species data. In order to pre-populate the species collection, I converted a csv file provided by UH Landscaping to JSON format, first condensing some of the redundant columns using excel functions to prevent data loss. I built the webpages to view and edit your user profile, add-to and edit a list of contacts, and pages to view and edit species information. The page to view all species is pictured above, which links to more detailed information in each species' profile, and the edit species pages. I created support for multiple users by filtering the contact list by the user who create the entry. Similarly, the user profile filters a list of individual plants and their locations to just those created by the current user (plant locations added by other users can be viewed elsewhere in the app).

For this project, our team met regularly in person, and communicated nightly via slack. It was really interesting to experience the advantages of github for file syncing in a team setting, although it did take some experimenting to get gitignore configured appropriately to ignore our individual log files. Once things were running smoothly, we still announced and coordinated changes to master, and were largely able to avoid incompatible merges. To coordinate our workflows we used a system of milestones (objectives for every 10 or so days) and non-overlapping issues (each about a couple days' of work for one individual); you can view our milestones M1, M2, and M3 [here](https://github.com/LetUmGrow/LetUmGrow/projects), documenting our indivual tasks. As part of the development plan, we have milestones to further develop the app (some of the team members will continue working on the project in future semesters).

As part of the assigment requirements, our app requires login via the UH servers, so a UH login is required to view the deployed version.

[LetUmGrow Landing Page](https://letumgrow.github.io/).

[LetUmGrow Source Files](https://github.com/LetUmGrow/LetUmGrow).
