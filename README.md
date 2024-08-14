## README for SGPA Calculator

### Overview

This SGPA Calculator is a simple web-based tool to calculate the Semester Grade Point Average (SGPA) required to achieve a desired Cumulative Grade Point Average (CGPA). Additionally, it can calculate the new CGPA after completing future credits with a known SGPA. The tool is built using HTML, CSS, and JavaScript.

### Files

1. **index.html**: The main HTML file containing the structure of the SGPA calculator.
2. **style.css**: (Optional) A CSS file can be used to move styles from inline `<style>` tags to a separate file.
3. **script.js**: (Optional) A JavaScript file for separating JavaScript logic from the HTML file.

### Features

- **Calculate SGPA**: Given your current CGPA, total credits, future credits, and desired CGPA, this tool calculates the SGPA you need to achieve in future semesters to reach the desired CGPA.
- **Calculate CGPA**: Given your current CGPA, total credits, future credits, and expected SGPA, this tool calculates your new CGPA after completing the future credits.
- **User-friendly Interface**: A simple and clean user interface, styled with CSS, for ease of use.
- **Responsive Feedback**: Provides instant feedback and loading animations while calculations are performed.

### Instructions

1. **Input Fields**:
   - **Total Credits**: Enter the total number of credits you have completed so far.
   - **Future Credits**: Enter the number of credits you plan to complete in future semesters.
   - **Desired CGPA**: Enter the CGPA you wish to achieve after completing future credits.
   - **Current CGPA**: Enter your current CGPA.
   - **Future SGPA**: (For CGPA Calculation) Enter the SGPA you expect to achieve for the future credits.

2. **Calculate SGPA**:
   - Click on the "Calculate SGPA" button.
   - The tool will display the SGPA you need to achieve in future semesters to reach your desired CGPA, along with the maximum SGPA and maximum possible CGPA.

3. **Calculate CGPA**:
   - Click on the "Calculate CGPA" button.
   - The tool will display the new CGPA you will achieve based on your expected SGPA for future credits.

### Technologies Used

- **HTML**: For the structure of the web page.
- **CSS**: For styling the elements, including form fields, buttons, and results.
- **JavaScript**: For handling calculations and displaying the results.

### Customization

- **Styling**: You can modify the styling in the `<style>` tag or move it to a separate `style.css` file for easier maintenance.
- **JavaScript Logic**: The calculation logic is currently embedded within the `<script>` tag. You can refactor this code to a separate `script.js` file.

### Example Use Case

- A student wants to calculate the SGPA needed to achieve a target CGPA after completing future semesters.
- The student can also use the calculator to estimate their new CGPA based on their expected SGPA in future semesters.

### License

You can add your preferred license for this project, such as MIT, GPL, or any other open-source license.

### Contribution

Feel free to contribute by improving the code, adding new features, or enhancing the UI/UX.
