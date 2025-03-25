# CodeAlpha_AGE_CALCULATOR
# Age Calculator

## Overview
This is a simple web-based Age Calculator built using **HTML, CSS, and JavaScript**. It calculates the user's age in **years, months, and days** based on their inputted date of birth.

## Features
✅ Simple and user-friendly UI  
✅ Takes date input from the user  
✅ Calculates age accurately  
✅ Displays result in years, months, and days  
✅ Responsive design for mobile and desktop users  
✅ Validates user input  

## File Structure
```
Age-Calculator/
│── index.html      # Main HTML file
│── style.css       # Stylesheet for UI
│── script.js       # JavaScript logic
│── README.md       # Project documentation
```

## How to Use
1. Open `index.html` in any web browser.
2. Enter your **Date of Birth** in the input field.
3. Click the **"Calculate Age"** button.
4. The calculated age will be displayed below the button in the format:
   ```
   You are X years, Y months, and Z days old.
   ```

## Code Explanation
### **HTML (`index.html`)**
- Creates a simple form with an input field for the date of birth and a button to trigger the age calculation.
- Displays the calculated age in an `<h3>` element.

### **CSS (`style.css`)**
- Adds styling to make the UI user-friendly and responsive.
- Centers the content and applies a modern look using box shadows and rounded corners.

### **JavaScript (`script.js`)**
- Retrieves the **date of birth** from user input.
- Uses the `Date` object to calculate the difference between the **current date** and the **entered date**.
- Adjusts for negative days and months to ensure correct age calculation.
- Displays the result dynamically inside the page.

## Requirements
- Any modern web browser (Chrome, Firefox, Edge, etc.)
- No additional libraries or frameworks needed

## Future Enhancements
🔹 Show countdown to next birthday  
🔹 Display Zodiac sign based on the date of birth  
🔹 Add dark mode for better UI experience  

## License
This project is **open-source** and free to use or modify.

---
💡 **Feel free to contribute and improve this project!** 🚀

