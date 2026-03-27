# Simple Interest Calculator

## 📌 Description
This is a simple program to calculate Simple Interest based on principal amount, rate of interest, and time.

## 🧮 Formula Used
Simple Interest = (P × R × T) / 100

Where:
- P = Principal Amount
- R = Rate of Interest
- T = Time (in years)

## 💻 Example Code (Python)

```python
P = float(input("Enter principal: "))
R = float(input("Enter rate: "))
T = float(input("Enter time: "))

SI = (P * R * T) / 100

print("Simple Interest =", SI)
