# PWA_PROJECT
# To-Do List

This is a simple **To-Do List** application built using **HTML**, **CSS**, and **JavaScript**. The project is enhanced with **Progressive Web App (PWA)** features, making it installable and functional offline.
https://aianaaa.github.io/PWA_PROJECT/
## Features

- **Add Tasks**: Users can add tasks to their to-do list.
- **Mark Tasks as Completed**: Users can mark tasks as done or remove them.
- **Offline Support**: The application works offline using a Service Worker.
- **Installable**: Includes a manifest file, allowing users to add the app to their home screen.
- **Responsive Design**: The layout is optimized for both desktop and mobile devices.


## Technologies Used

- **HTML**: For structuring the application.
- **CSS**: For styling and layout.
- **JavaScript**: For dynamic functionality.
- **Manifest.json**: To define metadata for the PWA.
- **Service Worker (sw.js)**: To enable offline capabilities and caching.


## How It Works
 1. **Adding a Task**
   - Enter a task in the input field and press the "Add" button.
   - The task will appear in the list below.
 2. **Marking as Completed**
   - Click on a task to mark it as completed or remove it from the list.
3. **Offline Functionality**
   - The application caches essential files using a Service Worker.
   - If there's no internet connection, the app still loads and allows interaction.


## Installation

1. Open the application in your browser.
2. Click the **"Install"** button in the address bar (if available) or the "Add to Home Screen" option.
3. The app will now be available as a standalone application on your device.


## Project Structure

```plaintext
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # Main JavaScript file
├── manifest.json       # Manifest file for PWA
├── sw.js               # Service Worker for offline functionality
└── /icons              # Folder containing app icons
