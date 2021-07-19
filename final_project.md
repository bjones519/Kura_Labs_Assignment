# Female Health & Well-being App

## Description:
***An application for women to take control of their reproductive health and well-being. While also creating a safe space where they can share their thoughts and experiences.***

## Features:
* Cycle Tracking
  * Flow (Light, Medium, Heavy)
  * Ovulation Tracking
  * Symptoms
  * Mood
  * Birth Control
  * Discharge
  * Sex
* Blogs
* Weight loss app
  * Step Counter
  * Calories
  * Exercise
  * Water Intake
  * Diet recipes
* ChatBot/Assistant
* Graphs for Analysis of the different trackers
* Different modes (Cycle tracking, Trying to get pregnant, Already pregnant)

## Architecture: Microservice Architecture.
We chose to go with a microservice architecture because the app contains many features which are independent of each other e.g blog vs flow tracking. Keeping these features separate allows them to be independently deployable and scalable. These are concepts that we as devops people need to keep in mind. If some areas in the app are more in demand than others, we want an architecture that can scale with that demand - something we can’t do with a monolithic app.
