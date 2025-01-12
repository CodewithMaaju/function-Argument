# function-Argument
Use of function and arguments types
# # so lets move in the topic of Functions in the python
# #so we can say function is the block of code which is used to perform a specific task when call its name. 
# # so lets see how to create a function in python
def name (fname, lname):
  print("Hello", fname, lname)
name("Muaz", "Khan")  
print(name, "is a good boy")
# # so we can see that we have created a function in python and we can call it anytime by using its name
# now lets dicuss about the function arguments
# so there are four types of function arguments
#1st is Default arruguments
print("Please enter your first, middle and last name:")
def name (fname, mname , lname):
  print("Hello", fname, mname, lname)
# name(input(), input(), input())
#2nd is the key argument
#this is key = value
#3rd is the required argument 
def name(fname, mname, lname):
    print("Hello,", fname, mname, lname)
#we need to add third otherwise it will give us the errors
name("Peter", "Quill", "Ego")
#4th is the variable-length argument]
# is used to perform more function in the function
#two types of variable-length arguments
#1st is arbirtary arguments
# def name(*name): here you see the single star 
#2nd is the keyword arbirtary argument
#def name(**name): here you see the double star
print("enter your first second and third name separatly")
def name (*name):
  print("Good morning", name[0], name[1], name[2])
name (input(), input(), input())


#now lets see the example of the arbirtary arguments
print("enter your first second and third name separatly")
def name (**name):
  print("Good morning", name["fname"], name["mname"], name["lname"])
name (fname = input(), mname = input(), lname = input())
