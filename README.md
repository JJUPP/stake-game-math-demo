# stake-game-math-demo
Demo game logic and payout simulation for online casino-style games using Python and JS.
# Stake Game Math Demo 🎰

This project demonstrates the math and mechanics of a simple slot-style game, including both backend logic (Python) and a basic playable frontend (HTML/JS). It was built as a showcase for joining the Stake Engine development program.

## 🔧 Features

- Python-based payout logic and simulation engine
- Win probability and volatility tuning
- JavaScript demo game playable in the browser
- Fully client-side, ready to integrate into Stake's static file requirements
- Simulations with visualized results (via Jupyter Notebook)

## 🧮 Game Logic (Python)

The `slot_math.py` file contains:

- Reel strips and symbol weights
- Winline logic
- Payout calculation
- RTP simulation over thousands of spins

## 🕹️ Frontend Demo

Launch the `index.html` to play a simple browser slot game. Built with vanilla JS and CSS, mimicking a minimal Stake UI.

## 📊 Simulations

Run `simulations.ipynb` to generate win distribution histograms and RTP stats using matplotlib.

---

## 📂 File Structure

- `game_logic/`: Python engine for simulating outcomes
- `frontend_demo/`: Browser-playable slot demo
- `assets/`: UI assets and placeholder symbols

