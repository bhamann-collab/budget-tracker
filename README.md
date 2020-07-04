# Unit 18 PWA Homework: Online/Offline Budget Trackers

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Currently Completed Tasks
The manifest.json file and the service-worker.js file have been created and placed in the public folder. The manifest.json file have been populated and completed to suit. The service-worker.js file had the essential files cached such as index.html and style.css.

## Uncompleted Tasks
Couldn't figure out how to properly cache the index.html file and the style.css file through the service-worker.js file. The plan was to properly cache the nessesary files (index.html, style.css and index.js). Then cache an extra json file that stores data that has not yet been stored in the database. Once when we get internet access again, we call an API to the router to send the data from our new json file to store in the database.

