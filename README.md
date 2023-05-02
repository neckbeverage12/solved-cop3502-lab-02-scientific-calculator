Download Link: https://assignmentchef.com/product/solved-cop3502-lab-02-scientific-calculator
<br>
<h2>Overview</h2>

In this project students will build a scientific calculator on the command line. The program will display a menu of options which includes several arithmetic operations as well as options to clear the result, display statistics, and exit the program. The project is designed to give students an opportunity to practice looping. Type conversion, and data persistence.

<h2>Specification</h2>

When the program starts it should display a menu, prompt the user to enter a menu option, and read a value:

Current Result: 0.0

Calculator Menu

—————

<ol>

 <li>Exit Program</li>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication 4. Division</li>

 <li>Exponentiation</li>

 <li>Logarithm</li>

 <li>Display Average</li>

</ol>




Enter Menu Selection: <strong>1</strong>

If an option with operands (1-6) is selected, the program should prompt for and read <strong><u><sub>double</sub></u></strong><u> precision</u> floating point numbers as follows:

Enter first operand: <strong>89.1</strong>

Enter second operand: <strong>42</strong>

Once the two operands have been read, the result should be calculated and displayed, along with the menu:

Current Result: 131.1

Calculator Menu

—————

…

<h3>Operational Behavior</h3>

This calculator includes multiple behaviors that are unique depending on the input and operation specified; they are detailed in this section.




<u>Exponentiation</u>

For exponentiation, the first operand should be used as the base and the second as the exponent, i.e.:




If the first operand is 2 and the second is 4…            2<sup>4</sup> = 16




<u>Logarithm</u>

For logarithms, the first operand should be used as the base and the second as the yield, i.e.:




If the first operand is 2 and the second is 4…            log<sub>2</sub>4 = 2




<u>Displaying the Average</u>

As the program progresses, it should store the <u>total of all results</u> of calculation and the <u>number of calculations</u>. Note that this does <strong>not</strong> include the starting value of 0! The program should display the average of all calculations as follows:




Sum of calculations: 101.3

Number of calculations: 2

Average of calculations: 50.15




Note that the average calculation should show a maximum of <strong>two</strong> decimal places. The program should immediately prompt the user for the next menu option (<u>without redisplaying the menu</u>).




If no calculations have been performed, this message should be displayed:




Error: no calculations yet to average!




<h2>Extra Credit</h2>

<u>Using Results of Calculation</u>

You can earn 5% extra credit on this project by allowing the user to use the previous result in an operation. To add this feature, allow the user to enter the word “<strong>RESULT</strong>” in place of an operand; if the user does so, the program should replace this operand with the <u>result of the previous calculation</u> (or zero if this is the first calculation):




Enter first operand: <strong>89.1</strong>

Enter second operand: <strong>RESULT</strong>




<h2>Submissions</h2>

<strong>NOTE</strong>: Your output must match the example output *exactly*. If it does not, <strong><em>you will not receive full credit for your submission</em></strong>!




File:                 SciCalculator.java

Method:           Submit on ZyLabs




<u>Do not submit any other files</u>!




<h2>Sample Output</h2>




Current Result: 0.0




Calculator Menu

—————

<ol>

 <li>Exit Program</li>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication 4. Division</li>

 <li>Exponentiation</li>

 <li>Logarithm</li>

 <li>Display Average</li>

</ol>




Enter Menu Selection: <strong>7</strong>

Error: No calculations yet to average!




Enter Menu Selection: <strong>1</strong>

Enter first operand: <strong>0.5</strong>

Enter second operand: <strong>-2.5</strong>




Current Result: -2.0




Calculator Menu

—————

<ol>

 <li>Exit Program</li>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication 4. Division</li>

 <li>Exponentiation</li>

 <li>Logarithm</li>

 <li>Display Average</li>

</ol>




Enter Menu Selection: <strong>5</strong>

Enter first operand: <strong>-2.0</strong>               For EC, replace with <strong><sub>RESULT </sub></strong>

Enter second operand: <strong>-2.0</strong>




Current Result: 0.25




Calculator Menu

—————

<ol>

 <li>Exit Program</li>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication 4. Division</li>

 <li>Exponentiation</li>

 <li>Logarithm</li>

 <li>Display Average</li>

</ol>

Enter Menu Selection: <strong>6</strong>

Enter first operand: <strong>2</strong>

Enter second operand: <strong>0.5</strong>




Current Result: -1.0




Calculator Menu

—————

<ol>

 <li>Exit Program</li>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication 4. Division</li>

 <li>Exponentiation</li>

 <li>Logarithm</li>

 <li>Display Average</li>

</ol>




Enter Menu Selection: <strong>7 </strong>




Sum of calculations: -2.75

Number of calculations: 3

Average of calculations: -0.92




Enter Menu Selection: <strong>-10 </strong>

Error: Invalid selection!




Enter Menu Selection: <strong>0 </strong>

Thanks for using this calculator. Goodbye!


