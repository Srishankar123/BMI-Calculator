# 🏋️‍♂️ BMI Calculator (Python)

This Python program calculates the **Body Mass Index (BMI)** of a person based on their **weight (in pounds)** and **height (in inches)**.  
It then categorizes the BMI into different health ranges and provides feedback.  

---

## 📦 Features
- Takes **weight**, **height**, and **name** as input.  
- Calculates BMI using the formula:  
  ```
  BMI = (weight * 703) / (height * height)
  ```
- Classifies the result into:
  - Underweight
  - Normal weight
  - Overweight
  - Obese
  - Severely obese
  - Morbidly obese  

---

## ▶️ Usage

1. Run the script in Python:
   ```bash
   python bmi_calculator.py
   ```

2. Enter your details when prompted:
   ```
   Enter your weight in pounds: 170
   Enter your height in inches: 62
   Enter your name: Josh
   ```

3. Example Output:
   ```
   Josh, you are overweight. You need to exercise more and stop sitting and writing so many python tutorials.
   ```

---

## 📁 Project Structure
```
BMI-Calculator/
│
├── bmi_calculator.py   # Python script
├── README.md           # Project documentation
```

---

## 📝 Notes
- Ensure you enter valid **positive numbers** for weight and height.  
- The script currently uses **pounds** and **inches**. If you want to use **kg/cm**, you’ll need to adjust the formula:
  ```
  BMI = weight (kg) / (height (m)^2)
  ```

---
