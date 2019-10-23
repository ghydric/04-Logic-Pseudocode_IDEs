# Exercise Workbench
* Design a While loop that lets the user enter a number. The number should be multiplied by 10, and the result stored in a variable named product. The loop should iterate as long as product contains a value less than 100.
```
// Module main()
//Start
   
   //Declarations
   Declare Integer userNum, product
   Constant Integer TEN = 10
   Constant Integer MAX_PRODUCT = 100
   
   Do
      Prompt "Enter an integer to be multiplied by 10"
      Input userNum
      Set product = userNum * TEN
      Display product
   While product < MAX_PRODUCT

//Stop
```
* Design a Do-While loop that asks the user to enter two numbers. The numbers should be added and the sum displayed. The loop should ask the user whether he or she wishes to perform the operation again. If so, the loop should repeat; otherwise it should terminate.
```
//Module main()
//Start

   //Declarations
   Declare Integer num1, num2, sum
   Declare String userInput //user's answer to repeating the operation (USER_PROMPT3)
   Constant String USER_PROMPT1 = "Enter an integer"
   Constant String USER_PROMPT2 = "Enter another integer to be added to the first"
   Constant String USER_PROMPT3 = "Would you like to perform the operation again? Enter 'y' for yes."
   Constant String REPEAT = "y"

   Do
      Prompt USER_PROMPT1
      input num1
      Prompt USER_PROMPT2
      input num2
      set sum = num1 + num2
      Display "The sum of $0 and $1 is $2", num1, num2, sum
      Prompt USER_PROMPT3
      input userInput.tolower()
   While userInput == REPEAT

//Stop
```
* Design a For loop that displays the following set of numbers:

0, 10, 20, 30, 40, 50, . . . , 1000
```
//Module main()
//Start
   
   //Declarations
   Declare Integer num

   For (num = 0; num <= 1000; num + 10)
      Display num
   EndFor

//Stop
```
* Design a loop that asks the user to enter a number. The loop should iterate 10 times and keep a running total of the numbers entered.
```
//Module main()
//Start

   //Declarations
   Declare Integer i, userInput, total
   Constant Integer TEN = 10

   For (i = 1; i <= TEN; i++)
      Prompt "Enter a number"
      Input userInput
      total += userInput
   End For

   Display total
   
//Stop
```
* Design a For loop that calculates the total of the following series of numbers:
![image](https://user-images.githubusercontent.com/47218880/67423054-31740800-f599-11e9-9565-031c1f729e1c.png)

* Design a nested loop that displays 10 rows of # characters. There should be 15 # characters in each row.

* Convert the While loop in the following code to a Do-While loop:
```
Declare Integer x = 1
While x > 0
   Display "Enter a number."
   Input x
End While
```
* Convert the Do-While loop in the following code to a While loop:
```
Declare String sure
Do
  Display "Are you sure you want to quit?"
  Input sure
While sure != "Y" AND sure != "y"
```
* Convert the following While loop to a For loop:
```
Declare Integer count = 0
While count < 50
   Display "The count is ", count
   Set count = count + 1
End While
```
* Convert the following For loop to a While loop:
```
Declare Integer count
For count = 1 To 50
   Display count
End For
```
