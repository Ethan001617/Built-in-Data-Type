# Built-in-Data-Type
Once again I want to tell y'all that in Python we do not define data types., However, you should know that which data types are support in Python so that you can write programs better.

These Data type are provided by Python language

Following are the Built-in data type:-

None Type

Numeric Type

Seqences 

Sets

Mappings

This is not User difined data we'll see it seperately because it has an Array, Class which is very big topic.
It also has some big topics like. Lists, Tuple, Dictionary, Mappings.So we will take small introductions of this, but keep in mind that the rest have a very big concept, they have to be read in detail.so that you can write programs better.
So the basic that we see in all languages, we see them 

and then we will see the big topic separately.

# None Type
None Data Type represents an object that dosen't contain any value.
It is very similar to the Null type which is read in Java.

# Numeric Type
Following are the numeric Data Type:

Int

Float

Complex

# Int Data Type:

The Int Data Type represents an integer number. An integer number without any decimal point or fraction part. In Python, it is possible to store very large integer number as there is no limit for the size of an int datatype

Lets Understand With Example:
                            
                            Etha_n = 10
                            print(Etha_n)
#If you want to check its type , then there is a function for it
                            
                            type(Etha_n)
#It will give us which type of variable it is.                            
 
 # Float Type:
 The Float datatype represents floating numbers. A floating point number is a number that contains a decimal point
 
 Example:
        25.5, 15.5, 16.8, -0.8, -7.4
        
        price = 16.8
        run_rate = -0.8
        print(price)
        type(price)
        value = 5.1e5 (# here 5.1e5 is it is specific notation where e or E represents exponentation which represents the power of 10 [5.1 x 10(5)]
 # Complex:
 A Complex number is a number that is written in the form of a + bj or a + b. where
 
a = Real part of the number
 
 b = Imaginary part of the number 
 
 j or J = Square root value of -1 
 
 a and b may contain integer or float number
 
 Ex: 5+7j, 0.5+2J
              
              com = 5+7j
              print(com)
     
              type(com)
#It will give us which type of variable it is.

# Bool/Boolean Type:
The Bool Data type represents Boolean Value True or False. Python internally represents True as 1 and False as 0
EXAMPLE:
        As you ever do True + True, the output will be 2. OR True - False, The Output will be 1
          
          True + True = 2
          True - Flase = 1

So,...... much of this is used on the condition base

Example:
      
      2 is greater than 3 or not, if yes than True Other wise False, This way the result come. 

# Sequence Type:
Following are the Sequence Type

String

List

Tuple

Range

# String:
String represents group of characters. Strings are enclosed in double quotes or single quotes

Here the characters means Letters A,B,C,D,E...Etc...,
Example:

      "Hello", "Ethan", 'Mike'

If want to assign this thing in a variable, 

str1 = 'Ethan'  Here 'Ethan' is a string, is a group of characters. 

That's why this variable will be the 'string' data type variable

# List:
A List represents a group of elements. A list can store different type of elements (That means, the integer type can also be an element, it can be a string type, it can also be a float type). which can be modified. List are dynamic which means size is not fixed (Like if you have learned any language C or Java, then you can compare it with an array. where, First we fix the size of the array so that the number of elements in it will be as much as the array.). List are represented using square bracket [].


The basic difference between the list and the array is that in the array you can keep the same type of data and in the list you can keep different types of data.

Example:
        
       data = [10, 40, "Ethan", -50, 59.7]
if you want to access it then you can do like this
       
       print(data)
       
       Note: The first character has index 0. 
       0 = 10
       1 = 40
       2 = "Ethan"
       3 = -50
       4 = 59.7

If you want to modify it, you can do it like this

        data[Insert an index number that you want to change] = Enter the value you want
        suppose i want to change 40 value to 20 ;So i will do like this
        data[1] = 20
        here data is my variable name

This is the intro concept of list, we will see it in detail , there is a lot of things left to study because it has a very big concept

# Tuple:
a tuple contains a group of elements which can be different types. it is similar to list, but Tuple is Read-Only. which means we cannot modify it's element. Tuples are represented using parantheses()...

the difference between list and tuple is , The list is represented by square brackets and the tuple is reprensented by Parentheses.The rest of the work is almost same
NOTE:-  Remember I am using Almost word

So Example:- 

            data = (10, 40, "Ethan", -50, 59.7)
Can access the element by index number
            
            print(data[1])
            
            if Will try to change it's Value It will give an error as 'tuple' object does not support item assignment
            Like if i want to change 40 as 20 .....I Can't..
            
# Range:
range Represents a sequence of numbers. The numbers in the range are not mofifiable.

Example:-
I created a Range data type variable as Rg

                  Rg = range(6)                                 0,1,2,3,4,5
other than this You can also use more values Like

                  Rg = range(10,21,2)                           10,12,14,16,18,20
            
            It would mean That, Will start at 10 and Finish at 20, And there should be a difference of 2 between them
            
            
