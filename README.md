NAME: MOHITHA BATTU
ID: CT08DS1234
COMPANY: CODETECH IT SOLUTIONS
DOMAIN: JAVA
DURATION: 25/5/2024-25/6/2024(4 weeks)
MENTOR NAME: SRAVANI GOUNI
DESCRIPTION:

The core functionality is encapsulated in the `BasicCalculator` class, which contains the `main` method. The `main` method serves as the entry point of the program. When the program runs, it first declares two variables, `num1` and `num2`, of type `double` to store the numbers input by the user.

Using a `Scanner` object, the program prompts the user to enter two numbers. The `Scanner` reads these numbers from the console and assigns them to `num1` and `num2`. Next, the program asks the user to input an operator (`+`, `-`, `*`, `/`) to specify the desired arithmetic operation.

The user’s input for the operator is read as a character (`char op`). A variable `double o` is then initialized to hold the result of the computation. The program uses a `switch` statement to determine the operation based on the operator entered:
- In the case of addition (`+`), it adds `num1` and `num2` and stores the result in `o`.
- In the case of subtraction (`-`), it subtracts `num2` from `num1` and stores the result in `o`.
- In the case of multiplication (`*`), it multiplies `num1` by `num2` and stores the result in `o`.
- In the case of division (`/`), it divides `num1` by `num2` and stores the result in `o`.

If the user enters an invalid operator, the program outputs an error message: "You enter wrong input".

Finally, the program prints the result of the arithmetic operation in a formatted manner, showing the equation and its result (`num1 op num2 = o`). This output provides clear feedback to the user. This simple calculator demonstrates basic concepts of Java programming, including user input, conditionals, and arithmetic operations, making it an effective learning tool for beginners.
The BasicCalculator program in Java is a fundamental example of a console-based application that performs essential arithmetic operations. It showcases the core concepts of user input handling, conditional statements, and arithmetic calculations in a straightforward manner. By allowing the user to input two numbers and an operator, the program dynamically processes and outputs the result of the specified arithmetic operation.

CONCLUSION: 

This program serves as an excellent introductory project for beginners in Java programming, illustrating how to use the `Scanner` class for input, the `switch` statement for decision-making, and basic data types like `double` for numerical operations. Additionally, it emphasizes the importance of handling invalid input gracefully, as demonstrated by the error message for incorrect operators.

Overall, the BasicCalculator program provides a solid foundation for understanding the fundamental principles of Java programming and sets the stage for developing more complex applications in the future.
