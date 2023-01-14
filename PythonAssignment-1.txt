## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
A: Python can be used for multiple purposes like software development,scripting etc. hence it is called as a generate purpose language. 
It is called high level because it is easy to understand Python code by reading it.

Q2. Why is Python called a dynamically typed language?
A: Because the variables are checked only during run time.

Q3. List some pros and cons of Python programming language?
A: Pros: Easy to learn and use, open source,dynamically typed, multiple packages available for different purposes.
   Cons:code execution is slower, causes run time errors more, under developed database access

Q4. In what all domains can we use Python?
A: web development, data science, data analytics, machine learning, deep learning etc

Q5. What are variable and how can we declare them?
A: variables are pointers which store values. We can declare a variable by assinging a value. Example - a=300

Q6. How can we take an input from the user in Python?
A: We can use the " input()" function.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
A: String data type

Q8. What is type casting?
A: Type casting is converting one data type to another data type ex: coverting int to float

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
A: Yes, using the "split" function. Example:
   x, y = input("Enter two values: ").split()
   print("Number of boys: ", x)
   print("Number of girls: ", y)

Q10. What are keywords?
A: Keywords are predefined words for a specific language. They have to be used or called in a particular way.

Q11. Can we use keywords as a variable? Support your answer with reason.
A: No, Keywords are predefined and reserved words, hence cannot be used as a variable.

Q12. What is indentation? What's the use of indentaion in Python?
A: indentation is the space at the start of each line of code. Python uses indentaion to separate blocks of code.

Q13. How can we throw some output in Python?
A: using the "print()" function. ex: print('hello world') will provide " hello world " as output.

Q14. What are operators in Python?
A: Operators are used to perform specific operations in python.

Q15. What is difference between / and // operators?
A: / is the operator for division with decimal, // operator also performs division but rounds the output to the nearest whole number.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

A: x ='iNeuron'
   print(x*5)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
A: 
x=input('Enter a number\n')
y=int(x)
if y%2==0:
    print('The number entered is an Even number')
else:
    print('The number entered is an Odd number')


Q18. What are boolean operator?
A: The operators that result in boolean values ( True or False) are called as boolean operators. Example: AND , OR , NOT

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Q20. What are conditional statements in Python?
A: Conditional statements are ones which perform a specific actions depending on if a condition is met or not.

Q21. What is use of 'if', 'elif' and 'else' keywords?
A: IF condition is used to check whether a logical condition is met, ELIF and ELSE words are used to check for other conditions which are not part of the IF statement .
 Example: 
 x=input('Enter a number\n')
y=int(x)
if y%2==0:
    print('The number entered is an Even number')
else:
    print('The number entered is an Odd number')

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
A:
age=int(input('Enter your age\n'))
if age>=18:
    print('I can vote')
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A:

numbers = [12, 75, 150, 180, 145, 525, 50]
total=0
for x in numbers:
    if x%2==0:
        total=total+x
print(total)



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
A: 
x,y,z=input("Enter 3 numbers separated by spaces").split()
if x>=y and x>=z:
    print('The greatest number is x:',x)
if y>=x and y>=z:
    print('The greatest number is y:',y)
if z>=y and z>=x:
    print('The greatest number is z:',z)
exit()

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A:

numbers = [12, 75, 150, 180, 145, 525, 50]

for x in numbers:
    if x>500:
        exit()
    if x%5==0 and x!=150:
        print(x)

