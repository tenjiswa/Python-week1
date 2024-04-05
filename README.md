
# Python-week1
BASIC DATA TYPES
ints -1,2,0,15000323 are examples of integers in python there is no limit on the size of intergers
NON-DECIMAL INTERGER REPRESENTATION
in python,non-decimal integers like binary, octal (base8)and hexadecimal(base16) can be presented by adding a prefix as follows:
FLOAT is used to represent real numbers in python and it is written with a decimal point
BOOLEAN DATA TYPE
is used to represent any one of the two values, true or false
STRING
is a sequence of characters, double quotes or single quotes
NB:When working with strings,the plus sign is used to concatenate them but it cannot be used to add strings and numbers.
BASIC DATA STRUCTURES
list,tuples,sets,dictionaries,list comprehensions,dictionaries and comprehensions

LISTS is a collection of similar or different data types of items
example a list of natural numbers
1 2 3 4 5 6 7 8 9 10-LENGTH
0 1 2 3 4 5 6 7 8 9-INDEX
Starting index is always 0 and ending point its length-1

CREATING A LIST
Alist is created by placing items inside[] separated by commas
numbers=[1,2,3,4,5,6,7,8,9,10]

AN EMPTY LIST
number[]

A LIST WITH DUPLICATE ITEMS
numbers=[1,2,2,3,3,3,4,4,4,4]

A LIST WITH DIFFERENT DATA TYPES OF ITEMS
items=[1,2,'N',"GO",3.14159]

FEATURES OF A LIST
1.A list can have duplicate items
2.Items in a list are mutable
3.List can store items of various types
ACCESSING ELEMENTS OF A SINGLE DIMENSIONAL LIST
Single-dimensional list is a list where elements are listed one after the other
Each element is allocated a unique number xcalled index.
EXAMPLE A LIST CONTAINING MULTIPLES OF 5 UP TO 20
my_list=[5,10,15,20]
my_list= 5 10 15 20:LEN
         0  1  2  3:INDEX
To access element 5 we write the ff
my_list[0]=5
To access element 15
my_list[2]=15

NEGATIVE INDEXING
Accessing element from the last.
EXAMPLE A LIST CONTAINING MULTIPLES OF 5 UP TO 20
my_list= 5 10 15 20
         0  1  2  3:INDEX
        -4 -3 -2 -1:NEGATIVE INDEXING
TO access element 20, through its -index
my_list[-1]=20
To access element 5
my_list[-1]=5

ACCESSING ELEMENTS ON A MULTI-DIMENSIONAL LIST
List containing another list
EXAMPLE my_list2=[[1,2,3],"Neso",[4,5,6]]
To access value/element 1
my_list2[0][0]=1
To access the whole list [4,5,6]
my_list2[2]=[4,5,6]

ADDING AN ELEMENT TO A LIST
Elements can be added to a list in different ways, the following are the methods to add elements to a list
1.append()
2.insert()
3.extend()
APPEND() METHOD:A built-in method used to add an item at the end of a list
syntax list.append(value)

INSERT() METHOD:A built-in method used to add an item at a specific position
syntax list.insert(position,value)

EXTEND() METHOD:A built in method used to add all items of one list in another list
syntax list.extend(list2)

INPUT() METHOD:Used to take the input from the user, the user input is always converted to a string
syntax nam=input()
Input() Method with a message 
syntax number=input("enter a number")

INTRODUCTION TO TUPLES
Acollection of items which are indexed,ordere and immutable
syntax tuple_name=(item1,item2,item3...)
1.We cannot change,remove or add any items in a tuple
2.The order remain the same throughout the program
3.we can have duplicates

LENGTH OF ATUPLE
Can be determined using the len() function
EXAMPLE cars=('Audi','Mercedes','BMW')
len(cars)

THE TUPLE() CONSTRUCTOR
Alternative way to create a tuple
example cars=tuple(( 'audi','mercedes','bmw'))

USING A WHILE LOOP:Python use while loop and len() function to determine the length of the tuple, then start at 0 and loop your way through the tuple items by referring to their indexs
(NB:Remember to increase the index by 1 after each iteration).

EXAMPLE print all items using a while loop to go through all the index numbers:
SYNTAX
thistuple=("apple","banana","cherry")
   i=0
   while i<len(thistuple):
   print(thistuple[i])
   i=i+1
YOU CAN JOIN TWO TUPLES USING THE + OPERATOR
tuple1=("a","b","c")
tuple2=("1,2,3)
tuple3=tuple1+tuple2
print(tuple3)

TUPLE METHODS:
count() returns the number of times a specified value occurs in a tuple
index() searches the tuple for a specified value and returns the position of where  it was found

INTRODUCTION TO DICTIONARIES
A collection of key values pairs, allows us to store and retrieve values based on the keys on where to map and organize data efficiently.
SYNTAX
dict_name={key1:value1,key2:value2:}
Example 
car={'brand':'Audi','model':'q7'}
Dictionary can not have two items with the same key
Key-value that comes last will always be available in a dictionary
Dictionaries are mutable

LENGTH OF A DICTIONARY
Can be determined using the len() function
Gives the count of key-value pairs of a dictionary
EXAMPLE 
car={'brand','audi','model','97'}
len(car)
THE DICT() CONSTRUCTOR
Alternative way to create a dictionary
Keys are not rubbed within single or double quotes also in place of colunms we have equal signs.
INTRODUCTION TO LIST COMPREHENSION
Provides a shorter syntax while creating a new list from the existing list on basics of some condition
EXAMPLE
names=['John','Jame','Emmy','Michael','Jimmy']
j_names=[]
for name in names


   




