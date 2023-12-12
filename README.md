# Python
Python Language

# Intro to python

 To print some thing use below command use double quotes to display on screen

  
 `````````````````````````````
      print("Hello World")
```````````````````````````````


  If we not use doubt quotes it will execute the operation and display the result on screen 
  In below example we used an operand + in between. In that place we can use any operand to execute and display.

  
      `````````````````
      print(2 + 5)
      ``````````````````

      
How to print length of a variable?


````````````````````````
      print(len"abcd")
`````````````````````````


How to print a Hi Jack on display?


`````````````````````````````````````
 username = input()
 print("Hi" + " " + "Jack")
`````````````````````````````````````

 
How can we take particular(0th) index part in a string?


````````````````````````````````````````````````````
  x = "12 * * 34"
  print(x[0])  ; # output will be 1 in string "x"
`````````````````````````````````````````````````````


Assigning a variable and mathematical operations on it


```````````````````````````
a = 2
print(a)
expected output --> 2
a = a + 1
print(a)
expected output --> 3
```````````````````````````


  Order of Operations


````````````````
BODMAS --> B (Braces) , Order (Like squares, square_root, power of a variable), D (Division), M (Multiplication), A (Addition), S (Substraction).
``````````````````````





## input and output 

String concatenation 


``````````````````````````
username = input()
print("hi " + username)
````````````````````````````


Input is Satya


``````````````````````````````
expected output is "hi Satya
```````````````````````````````


We cannot concatinate value with a string we can add 2 strings. Below code throws an error


```````````````````````````````
a = "*" + 10
```````````````````````````````


in this case * is a string and 10 is a value so it cannot do operation on string with a value


String Repetition


`````````````````````````
a = "*" * 10
print(a)
expected output :  ********** ;# 10 stars should come as we multiplied it with 10
`````````````````````````


Another Example


``````````````````````
s = python
s = ("*" * 3 + s + "*" * 3)
print(s)
``````````````````````



Length of a variable 


````````````````````````````````````
username = input()
length = len(username)
print(length)
````````````````````````````````````````


Take input from user


```````````````````````````````````
username = input()
age = input()
print(username + "is" + age + "years old")
`````````````````````````````````````


Acessing characters in string
SATYA is a string. How tool will store this string is below format


``````````````````````````````
S A T Y A
0 1 2 3 4
````````````````````````````````````


How to access this values is in below format


````````````````````````````````````````````````````````
a = "Satya"
first_letter = a[0]
third_letter = a[2]
print(first_letter third_letter)
#expected output is "S t"
````````````````````````````````````````````````````````


We can try to use True OR False on operations as well


``````````````````````````````````````````````````````
p = 4
q = 7
r = ((5+p) < (7-q))
print(not (r and false))
#expected output is "True"
```````````````````````````````````````````````````````


## Slicing

``````````````````````````
message = "Hi Ravi"
part = message[3:7]
print (part)
!!!!!!!!!!!!!!!!!!!!!!!!!!!
output - Ravi
````````````````````````````

### check data type

type()


input : print(type(x))
outputs will give data type of x [whether it is an integer or string or float something like that]


output: int  [since 10 is an integer type]


Conversions -
int()  --> converts to integer data type


float() --> converts to float data type


str() --> converts to string data type


bool() --> converts to boolean data type



## Relational Operators 


Relational operators are used to compare valuses. We will duscuss on this side in next codes.

< - less than
> - greater than 
== is equal to
!= is  not equal to
>= greater than or equal to
<= less than or equal to



```````````````````````
first_string = input()
second_string = input()
```````````````````````


## Conditional Loops 

How to use if loop in python?

``````````````````````````````````````
if condition:
     <body>
else :
     <body>
``````````````````````````````````````


giving an example for reference


`````````````````````````````````````````````
Example 1 :-
first_number = int(input())
second_number = int(input())
if first_number > second_number:
      print(greater_number = first_number)
else :
      print(greater_number = second_number)
print(greater_number)


Example 2 :-
number = int(input())
remainder = number % 2
is_even = (remainder = 0)
if is_even:
     print("given number is even")
else :
     print("given number is odd")
`````````````````````````````````````````````


## exponential 


``````````````````````````````````````````````````````````````````
print(2*3)
output is 6
print("2"*3)
output is 222
===================================
how to write an exponential term
===================================
print(2**3)
outputs is 8 (2 exponential 3 is 8 = 2 * 2 * 2)
````````````````````````````````````````````````````````````````````



# Loops 


## While loop


```````````````````````````````````````````````````````
while condition:
     <body>
```````````````````````````````````````````````````````


````````````````````````````````````````````````````````
a = int(input())
counter = 0
while counter < 3:
    a = a + 1
    print(a)
    counter = counter + 1
    print("end")
````````````````````````````````````````````````````````


Will see another example as well for while loop


````````````````````````````````````````````````````````````
a = input()
counter = 0
length_of_a = len(a)
while counter < (length_of_a - 1):
    print (a[counter])
    counter = counter + 1
````````````````````````````````````````````````````````````
 





