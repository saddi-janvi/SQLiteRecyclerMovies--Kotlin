# SQLiteRecyclerMovies--Kotlin
# Android Movie App

This Android app allows users to manage a local movie SQLite database, display movie information through a RecyclerView, and download movie images from the internet.

## Table of Contents
1. [RecyclerView Modification](#recyclerview-modification)
2. [Database Management](#database-management)
3. [Movie Image Loading](#movie-image-loading)
4. [Demo and Testing](#demo-and-testing)

### Task 1
Create a helper class extending `SQLiteOpenHelper` to manage the local movie SQLite database. The class should handle the creation, loading, and management of the database.

## 2. RecyclerView Modification

### Task 2
Modify the existing RecyclerView adapter to fetch movie data from the SQLite database using the helper class implemented in Task 1.

## 3. Database Management

### Task 3
Save the database to a movie database file from Android Studio. Open the database using the SQLite Database Browser, delete and modify movies using SQL commands. Provide evidence for these actions.

## 4. RecyclerView Operations

### Task 4
Implement duplication and deletion of movies within the RecyclerView. Verify the success of these operations by saving the database, opening it with the SQLite Database Browser, and showing evidence of added and deleted movies.

## 5. Movie Image Loading

### Task 5
Load movie images from the internet using the movie poster or backdrop URI. Do not use local images from the drawable resource. Demonstrate the absence of local movie images and provide evidence of image loading from the internet.

### Overview

This Android Movie App is designed to provide users with a seamless experience managing their movie collection. The app utilizes a local SQLite database to store movie information and leverages a RecyclerView to display the data. Additionally, it supports downloading movie images from the internet for an enhanced visual experience.

### Prerequisites

Before using the app, ensure the following prerequisites are met:

- Android Studio installed
- Internet connection for downloading movie images

### Installation

Follow these steps to install and set up the Android Movie App:

1. Clone the repository: `git clone [repository_url]`
2. Open the project in Android Studio.
3. Build and run the app on an emulator or physical device.

### Usage

Once the app is installed, follow these steps to use it:

1. Explore the movie collection in the RecyclerView.
2. Perform duplication and deletion operations to manage your movie database.
3. Enjoy the visual experience with movie images loaded from the internet.
