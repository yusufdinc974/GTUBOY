# 🎮 GTU Boy – The Game Console  
## 🏆 Group 13 Project  

### 🖥️ **Project Type:** Arduino-based Game Console  
### 🎯 **Objective:** Develop a game console using Arduino to play classic games  

---

## 📌 **Project Overview**  
GTU Boy is an **Arduino-powered game console** featuring:  
✅ **Memory Game** with three game modes  
✅ **Snake Game** implemented on a **16×2 LCD**  
✅ **Easter Egg:** A **Russian Roulette mode** using LED lights  
✅ **Interactive Button Controls** for user input  

📽 **Watch the Demo Video:**  
[🎥 GTU Boy Demo](https://www.youtube.com/watch?v=lZX1WQwWp-4)  

---

## 🎮 **Games Implemented**  
### **🔹 1st Game – Memory Game**  
A classic memory-based challenge where players must recall LED sequences.  
**Three Game Modes:**  
1️⃣ **Standard Mode** – Adds **one LED** per round.  
2️⃣ **Randomized Mode** – Starts with **four LEDs** and **shuffles the sequence** every round.  
3️⃣ **Reversed Mode** – Same as Mode 2, but **players must input the sequence in reverse**.  

### **🔹 2nd Game – Snake**  
The famous **Snake game** implemented on a **16×2 LCD display**.  
- Uses a **linked list** to represent the snake.  
- **Predefined 8-character custom bitmaps** simulate movement.  

### **🔹 Easter Egg – Russian Roulette**  
- A hidden **multiplayer mode** (2-4 players).  
- Players press buttons in turn; **one unlucky player is eliminated** at random.  
- **Game was originally a bug**, but we **turned it into a feature**!  

---

## 🔧 **Hardware & Materials Used**  
- **Arduino Uno**  
- **20×20 PCB Board**  
- **Soldered Buttons & LEDs**  
- **16×2 LCD Display**  
- **Buzzer for sound effects**  
- **9V Battery for power supply**  

---

## 🛠 **How the Code Works?**  
- **Memory Game:**  
  - Generates a **random LED sequence**.  
  - Stores user input **in an array** for comparison.  
  - Validates sequence and **increments difficulty** per level.  

- **Snake Game:**  
  - Uses a **linked list** to represent the snake’s body.  
  - Detects **collision & food pickup** in a continuous loop.  
  - Renders the snake using **predefined LCD characters**.  

---

## ⚠️ **Challenges & Lessons Learned**  
🚨 **Biggest Challenges:**  
- Designing a **custom PCB for game controls**.  
- Debugging **unexpected LED flickering issues**.  
- Implementing **randomized sequences** in the Memory Game.  

💡 **Lessons Learned:**  
- **Collaboration is key!** Working in teams **solved problems faster**.  
- **Hardware debugging is time-consuming**, but **rewarding**.  
- **Even bugs can become game features!** (See: **Russian Roulette mode**).  

---

🚀 **Thank you for reading!** We had a blast making GTU Boy! 🎯  
