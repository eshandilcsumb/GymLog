# Overview and plan
The goal of this project is to work through all the steps necessary to create an app that uses the Room database wrapper for persistence and that allows users to login.

## Setup
1. Create a gitignore file
2. Create a branch
3. Make the initial project

## Basic functions
1. Add [View Bindings](https://developer.android.com/topic/libraries/view-binding)
2. Wire up the buttons
3. Read information from display
4. Log out information
5. Test the display

## Add the database
1. Add the room dependencies
    * [Android Room Dependency](https://developer.android.com/jetpack/androidx/releases/room)
2. Create the POJO entity objects
    * For now just a GymLog
3. Create database interface
4. Create the GymLog DAO
5. Make the repository
6. Use the Room repository to write/read logs
