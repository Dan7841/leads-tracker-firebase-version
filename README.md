# Leads Tracker - Firebase Version

A leads tracking app that saves URLs to a Firebase Realtime Database,
syncing data across devices in real time. An upgrade of an original
Chrome Extension Leads tracker which utilised localStorage.

## Features

- Save any URL as a lead with a single click
- Data persists across devices via Firebase Realtime Database
- Real time updates - changes reflect instantly
- Double click delete to clear all leads
- Environment Variables used to keep Firebase credentials secure

## Built With

- JavaScript (ES6 Modules)
- Firebase Realtime Database
- Vite
- HTML & CSS

## Screenshot

![Leads Tracker Screenshot](screenshot.png)

## Getting Started

### Prerequisites
- Node.js installed
- A Firebase account and Realtime Database set up

### Installation

1. Clone the repo
```bash
   git clone https://github.com/Dan7841/leads-tracker-firebase-version
```
2. Install dependencies
```bash
   npm install
```
3. Create a `.env` file in the root directory
```
   VITE_FIREBASE_DB_URL=your_firebase_database_url_here
```
4. Run the development server
```bash
   npm run dev
```

## Note

This project requires personal Firebase credentials to run.
A live demo is not available as the database is private.
Follow the setup instructions above to run it locally.

## Related Projects

- [Leads Tracker Chrome Extension](https://github.com/Dan7841/Leads-Tracker-Chrome-Extension) -
  The original localStorage version this project is based on.
