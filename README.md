# Elec3SoloProjects
# Quotes API (Random)

📜 Quote of the Day App

A modern Quote of the Day web application built using HTML, CSS, and JavaScript.
It fetches random quotes from an API, displays them with a typing animation, includes sound effects, and supports dark mode with theme persistence.

🌟 Features

🔄 Fetches random quotes from an API

✍️ Typing animation for quote and author

🎵 Button click sound effect

🌗 Light / Dark mode toggle

💾 Theme saved using localStorage

✨ Glassmorphism UI with animated gradient background

📱 Fully responsive (mobile-friendly)

🛠️ Technologies Used

HTML5 – Structure

CSS3 – Styling, animations, glassmorphism

JavaScript (ES6) – API fetching, DOM manipulation

Font Awesome – Quote icons

DummyJSON Quotes API – Quote source

🌐 API Used

DummyJSON Random Quote API

https://dummyjson.com/quotes/random

Sample API Response:
{
  "id": 1,
  "quote": "Your time is limited, so don’t waste it living someone else’s life.",
  "author": "Steve Jobs"
}

📂 Project Structure
quote-api/
│
├── index.html      # Main HTML file
├── style.css       # Styles & animations
├── script.js       # JavaScript logic
└── README.md       # Project documentation

🚀 How to Run the Project

Download or clone the repository

git clone https://github.com/your-username/quote-api.git


Open the project folder

Open index.html in your browser

No server required

Works fully offline except for API fetch

🌙 Dark Mode

Click the 🌙 / ☀️ button in the top-right corner

Theme preference is saved automatically

Uses CSS class toggling and localStorage

🎨 UI Highlights

Animated gradient background

Floating glass container effect

Smooth hover & transition animations

Mobile-responsive typography


🧠 What You’ll Learn From This Project

Fetching data from an API using fetch()

Async / Await handling

DOM manipulation

CSS animations & keyframes

Dark mode implementation

UI/UX design fundamentals

📄 License

This project is open-source and free to use for learning and personal projects.

🙌 Credits

Quotes API: DummyJSON

Icons: Font Awesome

Sound effect: SoundJay

# Scientific Calculator

🧮 Scientific Calculator (Web)

A fully functional Scientific Calculator built using HTML, CSS, and JavaScript.
This calculator supports basic arithmetic, scientific functions, keyboard input, and has a clean, modern UI.

🌟 Features

➕ Basic operations: + − × ÷

📐 Scientific functions:

sin, cos, tan

log (base 10)

ln (natural logarithm)

√ (square root)

x^y (power)

🔢 Mathematical constants:

π (Pi)

e (Euler’s number)

⌫ Backspace / delete

🧹 Clear all (C)

⌨️ Full keyboard support

❌ Error handling for invalid expressions

🛠️ Technologies Used

HTML5 – Calculator layout

CSS3 – Styling & responsive grid layout

JavaScript (ES6) – Calculator logic & evaluation

📂 Project Structure
scientific-calculator/
│
├── index.html     # Calculator UI
├── calcu.css      # Styles
├── calcu.js       # Calculator logic
└── README.md      # Documentation

🚀 How to Run the Project

Clone the repository

git clone https://github.com/your-username/scientific-calculator.git


Open the project folder

Open index.html in your browser

No server required

Works offline

⌨️ Keyboard Shortcuts
Key	Action
0–9	Enter numbers
+ - * /	Operators
( ) .	Parentheses & decimal
Enter	Calculate
Backspace	Delete last character
Esc	Clear display
🧠 How It Works

User input is displayed in a text field

Mathematical functions are converted to Math.* equivalents

Expressions are evaluated using JavaScript’s eval() method

Errors are caught and displayed as "Error"

🎨 UI Design

Purple background with centered calculator

Neon-style display screen

Grid-based button layout

Color-coded buttons:

🟠 Operators

🟢 Equals

🔴 Clear

⚠️ Note

This project uses eval() for expression evaluation.
It is safe for learning and personal projects, but not recommended for production environments without proper input sanitization.

📄 License

This project is open-source and free to use for educational purposes.

# Weather API
🌤️ Weather App (No API Key)

A modern Weather Web App built using HTML, CSS, and JavaScript, powered by the Open-Meteo API.
It shows real-time weather, hourly charts, 7-day forecast, and supports city search with live suggestions — all without an API key.

🌟 Features

📍 Automatic location detection (via Geolocation API)

🔍 Search weather by city name

💡 Live search suggestions (autocomplete)

🌡️ Current temperature & condition

💧 Humidity and 🌬️ wind speed

📊 Interactive hourly charts:

Temperature

Precipitation

Wind

📆 7-day weather forecast

🕒 12-hour formatted hourly display

📱 Fully responsive UI

🔑 No API key required

🛠️ Technologies Used

HTML5 – Structure

CSS3 – Styling, glassmorphism & layout

JavaScript (ES6) – Logic, API handling

Open-Meteo API – Weather & geocoding

Google Fonts (Inter) – Typography

🌐 APIs Used
☁️ Weather Data

Open-Meteo Forecast API

https://api.open-meteo.com/v1/forecast

🗺️ City Search & Geocoding
https://geocoding-api.open-meteo.com/v1/search

🔄 Reverse Geocoding
https://geocoding-api.open-meteo.com/v1/reverse


✔️ Completely free
✔️ No authentication required

📂 Project Structure
weather-app/
│
├── index.html        # Main HTML file
├── styles.css        # App styling
├── script.js         # Weather logic & API calls
├── images/
│   └── bg.jpg        # Background image
└── README.md         # Documentation

🚀 How to Run the Project

Clone the repository

git clone https://github.com/your-username/weather-app.git


Open the project folder

Open index.html in your browser

No server required

Works instantly

⌨️ How to Use

Allow location access to get weather automatically

Or type a city name in the search bar

Select a suggestion or click Search

Switch between:

🌡️ Temperature

🌧️ Precipitation

🌬️ Wind

📊 Charts Explained

Temperature chart – Next 8 hours

Precipitation chart – Rain intensity comparison

Wind chart – Wind speed trend

Current hour is highlighted

🧠 What You’ll Learn From This Project

Working with REST APIs

Using Geolocation API

Handling live search & debouncing

Dynamic DOM rendering

Responsive UI design

Real-world weather data visualization

⚠️ Notes

Weather icons are placeholders and can be customized

Background image can be replaced in /images/bg.jpg

Designed for learning and portfolio projects

📄 License

This project is open-source and free to use for educational and personal projects.

# Stopwatch

⏱️ Stopwatch Web App

A simple and interactive Stopwatch built with HTML, CSS, and JavaScript.
Features lap tracking, start/stop/reset, and a dark mode toggle for a modern look.

🌟 Features

✅ Start, Stop, Reset functionality

✅ Lap recording (latest laps appear on top)

✅ Millisecond precision (00:00.00)

✅ Dark mode / Light mode toggle

✅ Responsive design

✅ Fully interactive buttons and keyboard-friendly

🛠️ Technologies Used

HTML5 – Structure of the stopwatch

CSS3 – Styling, grid layout, dark/light themes

JavaScript (ES6) – Stopwatch logic and lap tracking

📂 Project Structure
stopwatch-app/
│
├── index.html        # Main HTML file
├── style.css         # Styling & dark mode
├── script.js         # Stopwatch functionality
└── README.md         # Documentation

🚀 How to Run the Project

Clone the repository

git clone https://github.com/your-username/stopwatch-app.git


Open the project folder

Open index.html in your browser

No server required

Works instantly offline

⌨️ How to Use

Start – Begin timing

Lap – Record a lap (button disabled until started)

Stop – Pause timing

Reset – Reset timer and clear all laps

Dark Mode Toggle – Switch between dark/light themes

🧠 How It Works

Stopwatch uses Date.now() to calculate elapsed time

setInterval updates the display every 10ms

Laps are prepended to a list for easy viewing

Dark mode is toggled by adding/removing a dark-mode class on the body

🎨 UI Design

Centered stopwatch with clean and modern layout

Millisecond-precise digital display

Color-coded buttons with hover effects

Dark mode for comfortable nighttime usage

⚠️ Notes

This is a frontend-only app; no backend required

Timer works offline and requires no API

Designed for learning, portfolios, or personal projects

📄 License

This project is open-source and free to use for educational and personal projects
