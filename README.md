### data types & operators
#### 2 types operators

##### Arithmetic operators
#- '+ - * /'
#- '+' adds two operands (var) together
#- '-' substract
#- '*' multiply
#- '/' divide


#### comparison operators
#- '>' greater than
#- '<' less than
#- '==' equal to
#- '!=' not equal to
#- '>=' greater and equal
#- '<=' less and equal

````
a= 4
b= 2
print(a>b) #true
print(a<b) # false
print(a==b) #true
print(a != b) #true

print(a+b) #6
````

# functions methods builtin python

# what options are available in python's builtin library
#greeting = "Hello world"
#print(greeting)

#if we need to check if the letters are in string

#print(greeting.isalpha()) #true or false

# is it in lower case or upper case
#print(greeting.islower()) #boolean
#print(greeting.isdigit()) #boolean
#print(greeting.endswith("!")) #boolean
#print(greeting.startswith("H")) #boolean and case sensitive


### string concatenation casting

- #string indexing
# 'Hello world!'
# index in python starts with 0

# hello world!
#0123456789101112 (h is 0, e is 1, l is 2 ...)

#greeting= "Hello World"
        # 01234567891011
        #             -1 (d is -1, reverse starts with -1)
#print(len(greeting))
#print(greeting[-5]) # output o
#print(greeting[:5]) # output hello

#print only world in a print statement using slicing
# print 4th letter from left to right
#print 7 letter from right to left
# print 6 letter from left to right


#greetings = "Hello World!"

# print(greetings[0])
#
# strip() is used to remove spaces
````
example_string = "James       "
print(example_string)
print(len(example_string))
print(len(example_string.strip()))
````
#
#
# # welcome user with their name and welcome message - name & message must start with capital
#
# example_text = "here's some text with lot's of text"
# print(example_text.count("text"))
#
# # find a method to bring the statement in capital letter
#
# #print(example_text.capitalize())
# #print(example_text.islower())
#
# # how to replace text within the string
# print(example_text.replace("with ", "t "))


# concatenation & casting
# You can concatenation (join) strings together but you can not join string and integer,for that you need to convert integer into string
````
first_name = "James"
mid_name = "Bond"
last_name = "007"
age = 47
address= 33


 

print(first_name + " " + mid_name + " " +  last_name + " " + str(age))
````

 # select all lines that you want to comment and then press control plus /