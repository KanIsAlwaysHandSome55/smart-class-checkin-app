# Smart Class Check-in & Learning Reflection App

## Problem Statement
Students sometimes check attendance without being physically present in class. The university needs a system to verify that students are actually in the classroom.

## Target Users
- University students
- Course instructors

## Features

### Check-in
- Record GPS location
- Scan QR code
- Record timestamp
- Previous class topic
- Expected topic
- Mood before class

### Finish Class
- Scan QR code again
- Record GPS location
- What I learned today
- Feedback

## User Flow
Home → Check-in → Scan QR → Fill Form → Save  
Home → Finish Class → Scan QR → Reflection → Save

## Tech Stack
Flutter  
Geolocator (GPS)  
Mobile Scanner (QR)  
SQLite  
Firebase Hosting
