# -sequence_models-day1-markov_chain.py
# Autoregressive Model

## 🔍 What It Does:
Autoregressive (AR) models predict the next value in a sequence by using past values. It’s like teaching a model: “What comes next based on what has come before?”

## ⚙️ Equation:
Xₜ = c + φ₁Xₜ₋₁ + φ₂Xₜ₋₂ + ... + φₚXₜ₋ₚ + εₜ

Where:
- φ are parameters
- εₜ is the noise
- p = number of past steps used (order)

## 📊 Example Use:
- Stock price prediction
- Weather forecasting
- Time-series sequence generation

## ❗ Limitations:
- Assumes linearity
- Doesn’t handle long-range dependencies well
- Poor at context switching → leads into why we need RNNs
- ![image](https://github.com/user-attachments/assets/b6851f19-decb-447d-852b-dcfea22f7f4b)

![image](https://github.com/user-attachments/assets/8dd8db27-811a-4d4f-8248-bba9ad7e93c5)
