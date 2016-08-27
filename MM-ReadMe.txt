Project Title:tests

Maven project contains 2 scripts as below.

TaskOne:
Automating FB signup then deactivating the newly created account, signup details are read from XML file called TestNG.xml, I've used the PageObjects technique in the implementation where I've separated between business, pages and tests, also TestNG anotations are used.

TaskTwo:

Automating FB signin and logout where data are read from XLS file, I've used TestNG anotations and created one script for the task, also I used JXL library in reading excel data.

Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Prerequisities

- Jave jre 1.7+
- Eclipse IDE
- Maven Plugin
- Selenium client & Server Libraries
- JXL library

Known Issues:

- TaskOne
-- Script is tested on FF browser only.
-- Issue in Birthdate select fields as the browser stopped detecting the fields despite I'm using the correct code.
-- The rest of the scenario is developed but not tested.
-- The scenario is handling the happy path scenario where the user will be redirected to Add Friends page right after signup however this is not the only case as expalined below.
--- Account suspension is not handled
--- Account email confirmation is not handled
- The browser is always display the arabic version of FB that's why there's an extra step to switch it to English

- TaskTwo
-- Script is tested on FF browser only.
-- Signout using FB menu needs more investigation that's why I've made a workaround to overcome it.

Versioning

v1.0

Authors

Hala Marzouk.
