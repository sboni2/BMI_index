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

### 🔑 Key Concepts & Challenges

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

### 🚀 Why It Matters

This tool is a great entry point for learning:

* **Python basics**: functions, loops, exception handling
* **User interaction**: validating input and providing feedback
* **Simple health metrics**: turning math formulas into meaningful information

---

Feel free to include this in your **README.md** under the project title or introduction section. Let me know if you’d like a shorter tagline or bullet-style summary!

[1]: https://github.com/Akilapcj/BMI-calculator?utm_source=chatgpt.com "GitHub - Akilapcj/BMI-calculator: This project demonstrates how to ..."
[2]: https://github.com/danartech/BMI-Calculator_Python-Project?utm_source=chatgpt.com "danartech/BMI-Calculator_Python-Project - GitHub"
[3]: https://medium.com/%40mailtoamanshri/bmi-calculator-bignners-js-project-e75fd275f673?utm_source=chatgpt.com "BMI Calculator(Bignner's JS Project) | by Aman Shrivastav | Medium"
[4]: https://www.w3resource.com/projects/java/java-project-bmi-calculator.php?utm_source=chatgpt.com "Java Project - BMI Calculator - w3resource"
[5]: https://github.com/Shikhabadhan01/BMI-calculator?utm_source=chatgpt.com "Shikhabadhan01/BMI-calculator - GitHub"
