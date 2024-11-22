1. Imports:
   - React and useState hook from the 'react' package
   - StyleSheet, Text, View, and TouchableOpacity components from 'react-native'

2. App Component:
   - The main functional component that renders the entire calculator app

3. State Management:
   - Uses useState hook to manage three state variables:
     - displayValue: represents the current value displayed on the calculator
     - operator: stores the current arithmetic operator
     - firstValue: stores the first operand for calculations

4. Event Handlers:
   - handleNumberInput: updates displayValue when a number button is pressed
   - handleOperatorInput: sets the operator and stores the first value
   - handleEqual: performs the calculation based on the operator and operands
   - handleClear: resets the calculator state

5. UI Structure:
   - The app's UI is divided into two main sections:
     - Display container: shows the app title, current operator, and display value
     - Button container: contains all the calculator buttons arranged in rows

6. Button Layout:
   - Number buttons (0-9)
   - Operator buttons (+, -, ×, ÷)
   - Equal button (=)
   - Clear button (C)

7. Styling:
   - Uses StyleSheet.create to define styles for various UI components
   - Applies custom styles for different button types (numbers, operators, equal, clear)
   - Sets the overall layout, colors, and dimensions of the app

The app allows users to perform basic arithmetic operations, clear the display, and see the results of their calculations. The UI is designed to resemble a typical calculator layout with a yellow background and customized button styles.
