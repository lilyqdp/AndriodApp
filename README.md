# Android Photo App

A lightweight mobile application for browsing, organizing, and tagging photos on Android.

# Overview

Android Photo App is a custom-built mobile application developed using Android Studio (Java + XML). The project focuses on creating an intuitive photo-organization tool where users can:

Browse imported photos

Tag and categorize images

Search photos using autocomplete

View thumbnails with a clean, responsive layout

This project demonstrates mobile UI design, activity/intent flow, modular Java architecture, and user data handling on Android.

# Features
✔ Photo Importing

Uses Android Image Picker with ACTION_OPEN_DOCUMENT

Stores selected images as a String list of URI paths

Photo URIs are passed across activities via Intent

Supports persistent access to device images

✔ Thumbnail Display

Thumbnails rendered using:

ImageView components

A custom BaseAdapter for dynamic GridView/ListView rendering

Smooth scrolling optimized via efficient view recycling

✔ Tagging & Organization

Users can assign tags to images

Albums and tags are stored in Java data structures

Modular design keeps album logic separate from UI logic

✔ Search & Autocomplete

Implements an autocomplete search bar

Suggestions generated from existing tags

Results update live as the user types

# Tech Stack

Language: Java
IDE: Android Studio (Hedgehog / Jellyfish compatible)
UI: XML (ConstraintLayout, LinearLayout, GridView, etc.)
Core Android Components:

Activities

Intents

Image Picker

URI Handling

Adapters (BaseAdapter)
# GenAI Usage Disclosure

This project uses AI assistance responsibly to accelerate development.
GenAI (ChatGPT) was used for:

Setting up a basic Android Studio app structure

Generating starter Java and XML boilerplate

Providing guidance on updating AndroidManifest.xml

Debugging image-picker logic (ACTION_OPEN_DOCUMENT)

Converting standalone Java snippets into Android-compatible code

Suggestions for implementing autocomplete and adapters

All architectural decisions, debugging, implementation, and final integration were completed manually.

 # Project Structure
Android20/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/android20/
│   │   │   │   ├── MainActivity.java
│   │   │   │   ├── PhotoAdapter.java
│   │   │   │   └── (album/search/tag logic)
│   │   │   └── res/
│   │   │       ├── layout/*.xml
│   │   │       ├── drawable/
│   │   │       └── values/
│   └── AndroidManifest.xml
└── README.md

# Getting Started

Clone the repo:

git clone https://github.com/rashiva12/Android20


Open the project in Android Studio

Sync Gradle

Run on an Android emulator or physical device (API 28–34 recommended)

📎 GitHub Repository

🔗 https://github.com/rashiva12/Android20/tree/master
