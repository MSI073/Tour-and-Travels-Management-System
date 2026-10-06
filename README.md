# Tour and Travels Management System

A web app to manage tour packages and customer bookings, with a dashboard for bookings and revenue.

## Features
- Add and delete tour packages (destination: Puri, Darjeeling, Digha, Purulia; length: 3, 5 or 10 days)
- Create bookings by plan (Single, Couple, Group of 3, Group of 5) with automatic total price
- Update booking status: Pending, Confirmed, Cancelled
- Dashboard: package count, booking count, pending count, revenue and bookings by destination
- Works in demo mode (browser storage) or with Firebase Firestore

## Tech
HTML, CSS, JavaScript, Firebase Firestore

## Run it
Open `index.html` in a browser. It starts in demo mode.

## Connect Firebase
1. Create a project at https://console.firebase.google.com and add a Web app.
2. Create a Firestore database (start in test mode).
3. Paste your web app config into `FIREBASE_CONFIG` near the top of the script in `index.html`.
4. Reload the page. The badge at the top shows "Firebase connected".

Collections used: `packages` and `bookings`.

## Author
Md Saiful Islam - https://github.com/MSI073
