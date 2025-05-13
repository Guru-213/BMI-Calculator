
# 🧮 Body Mass Index (BMI) Calculator

This is a simple web-based **BMI (Body Mass Index) Calculator** that allows users to input their height and weight to calculate their BMI and determine their weight condition.

---

## 📁 Project Structure

```
├── index.html     # Main HTML page
├── index.js       # JavaScript logic for BMI calculation
├── style.css      # Styling for the app
```

---

## 🚀 Features

- Input fields for height (in cm) and weight (in kg)
- Calculates BMI on button click
- Displays the BMI value and the associated weight category:
  - Underweight
  - Normal weight
  - Overweight
  - Obesity
- Responsive and clean UI with modern styling

---

## 🔧 How It Works

### HTML (`index.html`)
- Provides the structure of the BMI calculator.
- Includes input fields, a button, and result display areas.
- Loads external CSS and JS files.

### JavaScript (`index.js`)
- Grabs values from the height and weight input fields.
- Converts height to meters and calculates BMI using the formula:
  
  \[
  	ext{BMI} = rac{	ext{Weight (kg)}}{	ext{Height (m)}^2}
  \]

- Displays the BMI and the corresponding weight condition.

### CSS (`style.css`)
- Gives the app a visually appealing look.
- Utilizes flexbox for layout, gradient backgrounds, and styled inputs/buttons.

---

## 🛠 Installation & Usage

1. Clone or download the repository.
2. Make sure all three files are in the same directory.
3. Open `index.html` in your browser.
4. Enter your height and weight, click the button, and view your BMI result.

---

## 📜 License

This project is open source and free to use.

---

## 🙌 Acknowledgements

This is a beginner-friendly project for practicing HTML, CSS, and JavaScript interaction.
