# BMI Calculator

A simple command-line tool in Python that calculates your Body Mass Index (BMI) based on weight and height, and then classifies it into health categories.

# What It Does

* Prompts you to enter your **weight (kg)** and **height (m)**.
* Calculates BMI using the formula:

* **Categorizes** the result:

  * *Underweight* (BMI < 18.5)
  * *Normal weight* (18.5 ≤ BMI < 24.9)
  * *Overweight* (25 ≤ BMI < 29.9)
  * *Obese* (BMI ≥ 30)
* Displays your BMI (rounded to two decimal places) and your health category.

---

# Key Concepts & Challenges

1. **User Input Validation**

   * Ensures numeric input and reasonable values (e.g., greater than zero).
   * Provides clear error messages for invalid entries.

2. **Accurate BMI Calculation**

   * Implements the standard BMI formula correctly.

3. **Health Categorization**

   * Applies established BMI ranges to determine weight status ([github.com][1], [github.com][2], [medium.com][3], [w3resource.com][4], [github.com][5]).

4. **Clean, User-Friendly Design**

   * Command-line interface with:

     * Modular functions (`calculate_bmi`, `classify_bmi`, `get_positive_float`)
     * Input loops for reliable data entry
   * Presents results clearly and concisely.

---

# Why It Matters

This tool is a great entry point for learning:

* **Python basics**: functions, loops, exception handling
* **User interaction**: validating input and providing feedback
* **Simple health metrics**: turning math formulas into meaningful information

---

![image](https://github.com/harshgithup/OIBSIP/assets/116560172/f1e2a430-2d4b-4810-a679-e85bd6cec1e1)
