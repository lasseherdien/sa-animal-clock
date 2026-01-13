# SA Animal Kill Clock

A real-time data visualisation tracking the scale of animal slaughter for food production in South Africa. This project serves as an educational tool to visualise the scale of food production and consumption in SA.

**[View Live Demo](https://sa-animal-clock.vercel.app/)**

## ℹ️ About
This static web application functions as a digital "tally counter." It takes annual South African slaughter statistics and calculates a "kill rate per second" to display a constantly ticking counter.

The goal is to provide a "real-time" perspective on annual data, which can often feel abstract when viewed as static numbers on a spreadsheet.

## Features
* **Real-Time Counter:** Smooth animation loop updates numbers every frame.
* **Time Travel Modes:** Toggle between three different timeframes:
    * **Since Arrived:** Counts up from 0 the moment the user opens the page.
    * **This Week:** Calculates total deaths since Monday morning.
    * **This Year:** Calculates total deaths since January 1st.
* **SA Themed UI:** Designed using the official South African flag colour palette (Green, Gold, Red).
* **Social Sharing:** Rich link previews (Open Graph & Twitter Cards) for sharing on WhatsApp and social media.
* **Responsive Design:** Works seamlessly on desktop and mobile devices.

## Data Sources (2025 Updates)
The counters are based on the most recent industry reports available.

| Category | Annual Count | Primary Source |
| :--- | :--- | :--- |
| **Chickens** | 1,125,000,000 | [SAPA Board Report 2024](https://www.sapoultry.co.za/) |
| **Cattle** | 2,800,000 | [RMIS](https://rmis.co.za/) / [BFAP 2025](https://rmis.co.za/) |
| **Pigs** | 3,800,000 | [RMIS](https://rmis.co.za/) / [BFAP 2025](https://rmis.co.za/) |
| **Sheep** | 5,500,000 | [RMIS](https://rmis.co.za/) / [BFAP 2025](https://rmis.co.za/) |
| **Wild Fish**| ~7.8 Billion | [StatsSA 2023](https://www.statssa.gov.za/) (Based on 600k tonnes) |
| **Farmed Fish** | ~200 Million | [StatsSA 2023](https://www.statssa.gov.za/) (Based on 10k tonnes) |
| **Ostriches** | 150,000 | [WC Dept. Agriculture](https://www.elsenburg.com/) |
| **Crocodiles** | 72,750 | [SA Online](https://southafrica.co.za/) / CITES |

## 🛠️ Technologies
* **HTML5** (Semantic structure)
* **CSS3** (Grid/Flexbox, Custom Variables, Animations)
* **JavaScript** (ES6+, `requestAnimationFrame` for performance)
* **SVG** (Vector icons for crisp display at any size)

## Project Structure
```text
/
├── index.html           # Main application logic
├── style.css            # Styling and animations
├── README.md            # Documentation
└── images/              # Assets
    ├── chicken.svg
    ├── cattle.svg
    ├── pig.svg
    ├── sheep.svg
    ├── ostrich.svg
    ├── crocodile.svg
    ├── wild-caught-fish.svg
    ├── farmed-fish.svg
    ├── favicon.png
    └── social-share.png
