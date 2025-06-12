# 📈 Sequence Models – Day 1

Welcome to Day 1 of my Machine Learning Mastery Series.  
Today's focus: **Autoregressive Models** and **Markov Chains**

---

## 🔁 Autoregressive Model (AR)

### 🔍 What It Does:
AR models predict future points in a sequence using past values.
Equation:  
**Xₜ = c + φ₁Xₜ₋₁ + φ₂Xₜ₋₂ + ... + φₚXₜ₋ₚ + εₜ**

### ✅ Applications:
- Stock Price Prediction
- Weather Forecasting
- Time-Series Forecasting

### 📊 Output Example:
![image](https://github.com/user-attachments/assets/5d032838-3265-45fa-8208-bb7d7c3f0ed7)


---

## 🔄 Markov Chains

### 🧠 Core Idea:
Next state depends **only on the current state**, not the full history.  
Known as the **Markov Property**.

### 📝 Use Cases:
- Text Generation
- Predictive Typing
- Game AI

### 🔧 Sample Output:
Generated sentence:  
`"the sun rises in the east and sets in the west"`

### ⚠️ Limitations:
- Cannot model long-term dependencies
- Memoryless → Not ideal for deep NLP tasks

---

## 📂 File Structure:
