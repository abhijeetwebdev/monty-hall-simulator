# 🎲 Monty Hall Simulator

An **interactive web-based Monty Hall problem simulator** that lets you play the game, run large-scale simulations, and see statistical proof of whether switching doors actually improves your odds.

---

## 📌 About the Project

The Monty Hall problem is a famous probability paradox that feels counterintuitive.
This project was built to **experimentally verify the claim** that switching doors gives a higher chance of winning—using real gameplay, simulations, and visual statistics.

**Conclusion:** Switching doors really does work.

---

## 🧠 How the Monty Hall Problem Works

1. Three doors: one car 🚗 and two goats 🐐
2. You pick one door
3. The host opens another door revealing a goat
4. You choose to **stay** or **switch**
5. Which strategy wins more often?

This simulator allows you to test both strategies manually and statistically.

---

## ✨ Features

* 🎮 **Interactive Gameplay**

  * Clickable doors with animations
  * Switch or stay using buttons or door clicks
  * Responsive and modern UI

* 📊 **Statistics & Visualization**

  * Manual game tracking
  * Automated simulations (10–100,000 games)
  * Real-time win percentages
  * Interactive bar chart (Switch vs Stay)
  * Persistent stats using LocalStorage

* ⚙️ **Simulation Engine**

  * Fully randomized logic
  * Configurable simulation size
  * Input validation and reset functionality

---

## 🚀 How to Use

### Play Manually

1. Open `index.html` in a browser
2. Select a door
3. Choose to switch or stay after a goat is revealed
4. Reveal the result
5. View stats in the **Manual Game** tab

### Run Simulations

1. Go to the **Simulation** tab
2. Enter the number of games
3. Click **Run Simulation**
4. View combined results in the **Overall** tab

---

## 📈 Results

After running tens of thousands of simulations:

* **Switching Strategy:** ~66.7% win rate
* **Staying Strategy:** ~33.3% win rate

Switching doubles your chances because your original choice has a 1/3 probability, while the remaining unopened door carries the other 2/3.

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling, animations, responsiveness
* **JavaScript (ES6)** – Game logic and simulations
* **Chart.js** – Data visualization
* **LocalStorage API** – Persistent statistics

---

## 📂 Project Structure

```
monty-hall-simulator/
├── index.html   # Complete app (HTML, CSS, JS)
└── README.md
```

---

## 👤 Credits

**Author:** Abhijeet Salunkhe  
**Built with:** Claude Sonnet 4.5 (via GitHub Copilot in VS Code)  
**Date:** February 2026

Built as a personal experiment to validate the Monty Hall paradox through simulation and visualization.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---
