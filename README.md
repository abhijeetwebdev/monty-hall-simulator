# Monty Hall Simulator

A **web-based Monty Hall problem simulator** that allows users to play the classic probability game, run automated simulations, and visualize the results using interactive charts. Designed to help understand the counter-intuitive advantage of switching doors.

---

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [How to Use](#how-to-use)
* [Simulation](#simulation)
* [Technologies Used](#technologies-used)
* [Project Structure](#project-structure)
* [License](#license)

---

## Overview

The Monty Hall problem is a famous probability puzzle based on a game show scenario:

1. There are three doors: behind one is a car, behind the others are goats.
2. The player picks a door.
3. The host opens one of the remaining doors, revealing a goat.
4. The player can **stay** with their original choice or **switch** to the other unopened door.

This simulator allows users to test both strategies (switching vs staying) and see the probability of winning using automated simulations and visual charts.

---

## Features

* **Interactive gameplay**: Pick a door, reveal a goat, choose to switch or stay, and see the result.
* **Automated simulation**: Run 1000 trials to see the probability of winning with either strategy.
* **Dynamic stats**: Total games, wins, and win percentages are updated in real-time.
* **Visual charts**: Bar chart displays Switch vs Stay win percentages clearly.
* **Responsive layout**: Works on desktop and tablet screens.

---

## How to Use

1. Open `index.html` in your browser.
2. Pick one of the three doors.
3. After a goat is revealed, decide to either **Switch** or **Stay**.
4. Click **Reveal** to see the result.
5. Click **Restart** to play again.

---

## Simulation

* Click **Run Simulation (1000)** to automatically simulate 1000 games.
* The simulator will calculate the total wins and win percentages for **Switch** and **Stay** strategies.
* Results are displayed in the stats box and bar chart.

> Typically, switching gives a ~66% chance of winning, while staying gives ~33%.

---

## Technologies Used

* **HTML5**: Structure of the simulator.
* **CSS3**: Styling, layout, and responsive design.
* **JavaScript**: Game logic, simulation, and stats calculations.
* **Chart.js**: Visualization of Switch vs Stay win percentages.

---

## Project Structure

```
monty-hall-simulator/
│
├── index.html      # Main HTML file containing game, controls, stats, and charts
└── README.md       # Project documentation
```

---

## License

This project is **MIT Licensed**, free to use, modify, and distribute.

---

**Author:** Abhijeet (Using GitHub copilot)
**Date:** 2026

---
