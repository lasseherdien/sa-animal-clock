# South Africa Animal Kill Clock

A real-time data visualisation tracking animal slaughter statistics in South Africa. This project serves as an educational tool to visualise the scale of food production and consumption in SA.

**[View Live Demo](https://sa-kill-count.netlify.app/)

## About
This static web application functions as a digital "tally counter." It takes annual South African slaughter statistics and calculates a "kill rate per second" to display a constantly ticking counter.

The goal is to provide a "real-time" perspective on annual data, which can often feel abstract when viewed as static numbers on a spreadsheet.

## Features
* **Real-Time Counter:** Smooth animation loop updates numbers every frame.
* **Time Travel Modes:** Toggle between three different timeframes:
    * **Since Arrived:** Counts up from 0 the moment the user opens the page.
    * **This Week:** Calculates total deaths since Monday morning.
    * **This Year:** Calculates total deaths since January 1st.
* **SA Themed UI:** Designed using the official South African flag colour palette (Green, Gold, Red).
* **Responsive Design:** Works seamlessly on desktop and mobile devices.

## Data Sources
The counters are based on estimated annual slaughter statistics for South Africa.
* **Chickens:** ~1.125 Billion / year
* **Sheep:** ~5.5 Million / year
* **Pigs:** ~3.8 Million / year
* **Cattle:** ~2.8 Million / year

*Data estimates derived from industry reports, including SAPA (South African Poultry Association) and DALRRD statistics.*

## Technologies
* **HTML5** (Semantic structure)
* **CSS3** (Flexbox/Grid, CSS Variables for theming)
* **JavaScript** (ES6+, `requestAnimationFrame` for performance)
* **SVG** (Vector icons for crisp display at any size)

## 📂 Project Structure
```text
/
├── index.html       # Main application file
├── images/          # Icon assets
│   ├── chicken.svg
│   ├── cattle.svg
│   ├── pigs.svg
│   └── sheep.svg
└── README.md        # Project documentation
