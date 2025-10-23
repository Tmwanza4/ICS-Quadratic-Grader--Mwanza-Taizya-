#ICS Quadratic solver & and grading system
## Description
This is a single web application that performs two tasks:
1. **Quadratic solver**
   -solves equations of the form `ax^2+bx+c=0`
   -validates input to ensure `a should not be equal to 0` and all inputs are numbers
   -calculates the discriminant `D is equal to b^2-4ac`
   -Determines the nature of roots
     - `D>0` - two distinct roots
     - `D<0` - two complex conjugate roots
     - `D=0` - one repeated real root
   -Displays roots neatly with 2 decimal places
2. **Grading System**
    -converts a numeric score (0-100) into a letter grade using this scale
     ```
     A+:85-100
     A:75-84
     B+:65-74
     B:60-64
     C+:55-59
     C:50-54
     D:0-49
  - Validates input and shows an error if the score is not within the range or not a number
  - outputs the result in the form: `score 82 - A.`
   ---
   ## How to Run
   1. Download or clone repository
   2. Open file `index.html`
   3. Follow the on-screen prompts or inputs:
      -Enter values for the quadratic solver (a,b,c) and click compute
      -Enter a score to calculate the letter grade.
   4. Use the reset buttons to clear inputs and results as needed

   ---
   ## Notes 
   - This program is self-contained and runs offline 
   - Error messages are displayed for invalid or missing inputs
   - Roots and grades are formatted clearly for readability.













   
