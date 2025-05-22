🕒 Theme Clock
A sleek analog + digital clock with light/dark theme toggle — built with HTML, CSS, and JavaScript.

✨ Features
Analog clock with smooth rotating hour, minute, and second hands
Digital time display with AM/PM format
Current date display with day and month
Light and Dark theme toggle
Built with pure JavaScript (no libraries)

🛠️ Tech Stack
HTML5 – Structure of the page
CSS3 – Styling and animations
JavaScript (Vanilla) – Real-time clock logic and interactivity

🧠 How It Works
Uses Date object in JavaScript to fetch real-time data every second.
Translates the time into angles for each clock hand:
hour hand rotates 30° per hour + offset for minutes.
minute hand rotates 6° per minute.
second hand rotates 6° per second.
Dark mode toggles a .dark class on the <html> element, changing CSS variables using :root.
