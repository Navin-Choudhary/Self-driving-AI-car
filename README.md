# 🚗 Self-Driving Car AI — Built in Pure JavaScript

A fully functional **self-driving car simulation** built **without any machine learning libraries**.  
The car uses **ray sensors, collision physics, neural networks and evolutionary learning** to teach itself how to drive and avoid obstacles.

🔗 **Live Demo:** https://self-driving-ai-car.netlify.app/   
💻 **Tech:** HTML, CSS, JavaScript (No libraries, No frameworks)

---

## 🧠 Project Features

| Component | Description |
|----------|-------------|
| Sensors | Detect road borders & nearby vehicles |
| Neural Network | Processes sensor inputs and outputs steering control |
| Evolutionary Learning | Mutation + natural selection to improve driving |
| Traffic Simulation | AI agents navigate through other moving cars |
| Visualizer | Real-time network visualization of neuron activations |
| Save/Load Brain | Train locally and store best performing model |

---

## 🎮 How it Works

1. A batch of AI cars is generated — each with a different random neural network.
2. All cars are released on the road with traffic obstacles.
3. The simulation identifies the **best-performing car** (farthest without a crash).
4. Clicking **`Save`** stores its **brain** to `localStorage`.
5. Clicking **`Discard`** resets learning.
6. After refreshing, new cars are generated from the saved brain with **small mutations** → improving over generations.

This creates **real self-driving behavior through evolution**, not training datasets.

---

## 🗂 Project Structure

📁 project
├─ index.html
├─ style.css
├─ main.js
├─ car.js
├─ sensor.js
├─ controls.js
├─ road.js
├─ utils.js
├─ network.js
├─ visualizer.js



---

## 🔥 Demo Controls

| Button | Action |
|--------|--------|
| **S** | Save best brain |
| **D** | Discard saved brain |

> AI drives automatically — no keyboard required.

If you switch the control type to `"KEYS"` in `main.js`, you can manually drive the car using **Arrow Keys**.

---

## 🖼 Preview

### AI learning over generations
- Initially crashes often
- Gradually avoids traffic
- Eventually learns to stay in lane and drive smoothly

### Neural Network Visualizer
Shows real-time:
- neuron activation levels
- weights & biases
- forward propagation per frame

---

## ⚙ Future Enhancements (coming soon / optional)

- Random traffic generator
- Multiple levels / maps
- Mutation slider (learning difficulty)
- Export / import neural network to `.json` file
- Leaderboard for best trained models

---

## 🙌 Credits

Inspired by the **self-driving car course by freeCodeCamp**.  

---

## ⭐ Contribute / Support

If you like this project:
- ⭐ Star the GitHub repo
- 🔄 Share the live demo
- 🧠 Try training the AI yourself



