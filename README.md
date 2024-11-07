# BMI-Calculator
Modules to Install

— Tkinter: This is a built—in Python module for creating graphical user interfaces (GUIs). If you're using the standard Python distribution, you don't need to install it separately.
— ttk: This module is part of Tkinter and provides themed widgets. It comes with Tkinter, so no separate installation is needed.

What the Code Does

This code creates a simple GUI application to calculate and display Body Mass Index (BMI). It also provides suggestions for weight and height ranges based on the user's inputs. Here’s how it works:

1. Creating the Application Window:
   — The application opens a window titled "BMI Calculator" and sets its size and background color.

2. Setting Up Input Fields:
   — There are fields where users can enter their weight and height.
   — Users can choose the unit for weight (kilograms or pounds) and the unit for height (meters or feet) from dropdown menus.

3. Calculate Button:
   — When users click the "Calculate" button, the application performs several tasks:
     — It retrieves the user's input values.
     — Converts the weight and height to metric units if necessary (pounds to kilograms and feet to meters).
     — Calculates the BMI using the formula: weight divided by the square of height.
     — Determines the BMI category (e.g., Underweight, Normal Weight, Overweight, Obese).
     — Displays the calculated BMI and its category on the screen.
     — Provides suggested weight and height ranges based on the calculated BMI.

4. Displaying Results:
   — The application updates the screen with:
     — The calculated BMI.
     — The BMI category.
     — Suggested weight and height ranges for maintaining a healthy BMI.

5. Error Handling:
   — If the user enters invalid data (e.g., non-numeric values), the application shows an error message asking for valid numerical inputs.

How It Works

1. Initialize the GUI:
   — The code sets up the main window and adds labels, entry fields, and dropdown menus for user input.
   — It also styles the button using a theme to make it look better.

2. Perform Calculations:
   — When the user clicks "Calculate", the application reads the input values, converts them if necessary, and calculates the BMI.
   — It uses predefined ranges to determine and display the appropriate weight and height suggestions based on the BMI.

3. Update the Display:
   — The results (BMI, category, suggested ranges) are shown on the application window.

This code provides a user-friendly way to calculate and understand BMI, offering additional guidance on maintaining a healthy weight and height based on user inputs.
