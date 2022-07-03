This assignment will allow you to begin using basic Python features. You will get to work with conditionals, loops, variables, functions, keyboard input, and console output.
This assignment satisfies the following course objective
C3: Apply skills to systematically test and debug applications
Armstrong Numbers
An Armstrong number (also known as a perfect or narcissistic number) is a number whose sum of each of its digits raised to the power of the count of digits in the number is the same as the number itself.  So if the number were 123 (which has 3 digits), you would evaluate as follows (note that the ** is the exponentiation operator in Python):

1**3 + 2**3 + 3**3

The result of the above operation would be 1 + 8 + 27, which is 36. This means 123 is not an Armstrong number.

Your job is to obtain a number n from the user that is greater than or equal to 10 and less than or equal to 100,000,000 (10 <= n <= 100000000). You must ensure a number in this range is entered.

You must then determine all Armstrong numbers from 10 through n.

Your program must then output those numbers, one per line starting with the smallest Armstrong number found. Format your output so that it is *identical* to what is shown below. Note that the x's and y's would have actual digits for the numbers found. The ... (ellipses) just says there may be more numbers and should not be included in your output.

Sample Run

Welcome to the Armstrong number calculator.
Please enter an integer from 10 through 100,000,000 (without the commas): 1000

The Armstrong numbers from 10 through 1000 are:
<blank line here>
xx
xxx
xxx
xxx
... 
<blank line here>
The total number of Armstrong numbers found was yy
Deliverables

Submit a zip file to Canvas with *your* last name, then first name, then assignment1 (e.g. capaultomassignment1.zip). The zip file must contain the following:

Your Python source file named armstrong.py
At the top of your source file place in a comment your name and a description of what the program is about (what it does)
Make sure your source code conforms to the Python conventions specified in this link: https://realpython.com/python-pep8/ (Links to an external site.)
Your source code should contain at least two functions. One for obtaining user input (perhaps get_user_input) and another to calculate the Armstrong numbers (calculate_armstrong_numbers).
A capture of your output from running the programming with inputs of
10
1000
10,000
100,000
1,000,000
10,000,000
100,000,000
9 (should print an error and re-prompt -- enter a 10 for correct input)
100,000,001 (should print an error and re-prompt -- enter a 10 for correct input)
You can capture your output by copying the results in PyCharm and pasting them into a plain text file. Name this plain text file armstrong_output.txt.
Note that moving forward we will learn to incorporate unit tests to handle the testing specified above!
A readme.txt file that contains the following information
How much time you spent on the assignment
Assignment problem areas (if there weren't any then just say 'none')
Any shortcomings your solution has (if there aren't any then just say 'none')
Any extra credit you attempted and successfully completed (if you did not attempt any you can leave this out)
(optional) Any questions you have for Tom
Extra credit: You can earn 3 points extra credit by ensuring the number entered by the user is an integer. Anything that is not an integer (string or float) should generate an error message and you should re-prompt for input continually until integer input in the proper range is entered. If you perform this extra credit be sure and document that you did so in your readme.txt.
Extra credit 2: You can earn 2 more points extra credit if you can tell me the time complexity (Big O) of your solution. You must justify your answer. Include this information in your readme.txt. NOTE: This is a TCSS 501 topic so you may need to refer to notes for that class or do an internet search to help you figure it out.
