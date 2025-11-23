Problem Statement :

The lack of a quick, accessible, and offline tool for performing fundamental arithmetic calculations often forces users to rely on complex applications or physical calculators for simple tasks. There is a need for a lightweight, terminal-based utility that can reliably handle basic mathematical operations (addition, subtraction, multiplication, and division) with immediate results and a continuous calculation option.

Scope of the Project :

1. Implementing the four basic arithmetic functions: addition, subtraction, multiplication, and division.

2. Handling integer and floating-point number inputs.

3. Implementing a robust input loop to allow for multiple calculations.

4. Implementing basic error handling for non-numeric input (ValueError).

Out of Scope:
1. Advanced mathematical functions (e.g., exponents, trigonometry, logarithms, modulus).

2. Scientific calculator features (e.g., memory, parentheses, order of operations).

3. A graphical user interface (GUI).

4. Handling the division by zero error (ZeroDivisionError).

 Target Users :
 
1. Students/Beginners: Individuals learning programming or basic mathematics who need a simple, distraction-free tool.

2. Developers/System Administrators: Users who frequently work in the terminal environment and require quick calculations without leaving their command line interface.

 High-Level Features :

1. Fundamental Arithmetic Operations: Support for the four basic functions (+, -, *, /) as distinct, modularized functions.

2. Interactive Menu Interface: A clear, numbered menu (1/2/3/4) that allows the user to easily select the desired operation.

3. Data Type Flexibility: The ability to accept and process both integers and floating-point numbers for calculations.

4. Runtime Input Validation: A mechanism to gracefully catch and handle non-numeric inputs from the user, preventing the program from crashing.

5.Continuous Calculation Loop: A built-in feature allowing the user to perform subsequent calculations without restarting the program.
