The simple calculator will perform basic arithmetic operations: addition, subtraction, multiplication, and division. The user interface will consist of a display area to show input and results, and buttons for digits (0-9), operations (+, -, *, /), and control functions (clear, equals).

Components
JFrame: The main window that holds all the components.
JTextField: A text field for displaying the input and result.
JButton: Buttons for digits, operations, and control functions.
JPanel: Panels to organize the buttons.
Layout
Display Panel: A panel at the top containing the JTextField.
Button Panel: A grid panel containing all the JButtons.
Steps to Create the Calculator
Set Up the Main Frame:

Create a JFrame and set its layout.
Set the default close operation to exit on close.
Create and Add the Display Field:

Create a JTextField for the display.
Set the JTextField to be non-editable so users can’t type directly.
Add the JTextField to the top of the JFrame.
Create and Add Buttons:

Create JButtons for digits (0-9), operations (+, -, *, /), and control functions (C for clear and = for equals).
Use an ActionListener to handle button clicks.
Organize the buttons in a grid layout within a JPanel.
Handle Button Clicks:

Implement the ActionListener interface.
Define the logic for each button press (e.g., appending digits, performing operations).
Update the display based on user input and operations.
