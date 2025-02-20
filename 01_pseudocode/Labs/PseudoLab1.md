|[Table of Contents](/00-Table-of-Contents.md)|
|---|

---

## PseudoLab1

**Draw Flowchart for pseudocode**

* Draw a flowchart or write pseudocode to represent the logic of a program that allows the user to enter a value for one edge of a cube. The program calculates the surface area of one side of the cube, the surface area of the cube, and its volume.  The progrma outputs all the results.

* Draw a flowchart or write pseudocode to represent the logic of a program that allows the user to enter two values.  The program outputs the sum and the differences between two values

* Draw a flowchart or write pseudocode to represent the logic of a program that allows the user to enter an hourly pay rate and hours worked.  The program outputs the user's gross pay.

* MOdify the program that computes gross pay to allow the user to enter the withholding tax rate.  The program outputs the net pay after taxes have been withheld.

* Research current rates of monetary exchange.  Draw a flowchart or write pseudocode to represent the logic of a program that allows the user to enter a number of dollasrs and convert it to euros and Japanese yen.

A mobile phone app allows a user to press a button that starts a timer that counts seconds.  When the user presses the button again, the timer stops.  Draw a flowchart or write pseudocode that accepts the elapsed time in seconds and displays the value in munutes and seconds.  For example, if the elapsed time was 130 seconds, the output would be 2 minutes and 10 seconds.

---

## Debugging Labs

**Find the errors**

* If the programmer translates the following pseudocode to an actual programming language, a syntax errror is likely to occur.  Can you find the error?

// fix actions below:
// variable 1stPrize cannot start with number
// it could be changed to firstPrize instead
// also there is a rogue apostrophe on line 40
```
Declare String 1stPrize

Display "Enter the award for first prize."
Input 1stPrize

Display "The first prize winner will receive "' 1stPrize
```

---

* The following code will not display the results expected by the programmer.  Can you find the error?

// fix actions below:
// parenthesis need to surround lowest + highest
// replace commas on line 61 with plus signs

```
Declare Real lowest, highest, average

Display "Enter the lowest score."
Input lowest

Display "Enter the highest score."
Input highest

Set average = low + high/2
Display "The average is ", average, "."

```

---

* Find the error in the following pseudocode

// fix actions below:
// Declare statement should be first in code

```
Display "Enter the length of the room."
Input length 
Declare Integer length

```

---

* Find the error in the following pseudocode

// fix actions below:
// sum should be set following the values1-3

```
Declare Integer value1, value2, value3, sum
Set sum= value1 + value2 + value3

Display "Enter the first value."
Input value1

Display "Enter the second value."
Input value2

Display "Enter the third value."
Input value3

Display "The sum of numbers is ", sum

```

---

* Find the error in the following pseudocode

// fix actions below:
// line 113 should be Set pi = 3.14159265
// replace period on line 114 with comma

```
Declare Real pi
Set 3.14159265 = pi
Display "The value of pi is ". pi
```

---

* Find the error in the following pseudocode.

// fix actions below:
// Gravity cannot be changed if set as constant
```
Constant Real GRAVITY = 9.81
Display "Rates of acceleration of an objet in free fall:"
Display "Earth: ", GRAVITY, " meters per second every second."
Set GRAVITY = 1.63
Display "Moon: ", GRAVITY, " meters per second every second."
```

---

|[Next Topic](/01_pseudocode/02_pseudocode.md)|
|---|
