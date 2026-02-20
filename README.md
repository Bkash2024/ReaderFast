# Read RSVP Speed Reader

A lightweight, dependency-free Rapid Serial Visual Presentation (RSVP) reader built with vanilla HTML, CSS, and JavaScript.

This tool is designed to help you read text significantly faster while reducing eye fatigue by utilizing the Optimal Recognition Point (ORP) to eliminate saccades (the natural side-to-side movements of your eyes while reading).

✨ Features

🎯 Optimal Recognition Point (ORP) Alignment: Words are not center-aligned; instead, the focal letter (highlighted in red) stays in the exact same physical position on the screen, keeping your eyes perfectly still.

🧠 Dynamic Pacing: The reading speed automatically adjusts based on punctuation and word length. It pauses slightly for commas, longer for periods, and slows down for long words, mimicking natural reading comprehension.

📱 iOS & PWA Ready: Can be added to your iOS or Android Home Screen for a native, app-like full-screen experience without browser toolbars.

☕️ Screen Persistence (Wake Lock): Uses the modern navigator.wakeLock API to prevent your device from dimming or going to sleep while you are reading.

🖥 Full-Screen Immersive Mode: Distraction-free reading mode with dimmed controls and enlarged text.

⌨️ Keyboard & Touch Controls: Press Spacebar to play/pause. On mobile, tap the text area directly to toggle playback.

⏪ Intelligent Rewind: Pausing the reader automatically rewinds the text by 5 words so you can regain context when you resume.

🚀 How to Use

On Desktop / Web

Clone this repository or download the index.html file.

Double-click the file to open it in any modern web browser.

Paste your text, set your desired Words Per Minute (WPM), and click Start Reading (or press Spacebar).

Note: The Wake Lock (Screen Persistence) feature requires the file to be hosted on a secure context (https:// or localhost).

On iPhone / iOS (Install as an App)

For the best mobile experience, install this as a Progressive Web App (PWA):

Host the file online (e.g., via GitHub Pages, Netlify, or Vercel).

Open the URL in Safari on your iPhone.

Tap the Share button (the square with an arrow pointing up) at the bottom of the screen.

Scroll down and tap "Add to Home Screen".

Launch the app from your home screen for a completely immersive, full-screen experience.

🎮 Controls

Start/Pause: Spacebar (Desktop) or Tap the text (Mobile Fullscreen)

Exit Fullscreen: Esc (Desktop) or Tap the dark background (Mobile Fullscreen)

🔬 The Science: How it Works

When reading traditional text, your eyes do not move smoothly across the page. They make quick, jerky movements called saccades, followed by brief stops called fixations. Your brain spends a significant amount of time just physically moving your eyes and finding the next word.

RSVP eliminates saccades entirely. By presenting words one at a time in the exact same location, your eyes remain stationary. The red letter in the display is the Optimal Recognition Point (ORP)—usually slightly left of the center of a word. By aligning the ORP of every word to the exact same vertical guide, your brain can process the word instantly without having to visually "search" for its center of gravity.

🛠 Tech Stack

HTML5: Semantic structure.

CSS3: Custom variables, flexbox, responsive design, and CSS transitions. Safe-area insets for modern mobile notches.

Vanilla JavaScript (ES6+): Class-based architecture, setTimeout recursive loops for dynamic timing, WakeLock API, and Fullscreen API. Zero external dependencies.

📄 License

This project is open-source and available under the MIT License. Feel free to fork, modify, and improve it!erFast
