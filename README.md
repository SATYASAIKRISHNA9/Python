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

======
input : print(type(10)) 
output: int  [since 10 is an integer type]
======

## Relational Operators 




 





