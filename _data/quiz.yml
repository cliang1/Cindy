import getpass, sys, os

def question_with_response(prompt):
    print("Question: " + prompt)
    msg = input()
    return msg

questions = 6
correct = 0

print('Hello, ' + getpass.getuser() + " running " + sys.executable)
print("You will be asked " + str(questions) + " questions.")
question_with_response("Are you ready to take a test?")

rsp = question_with_response("Which command allows people to import commands and funcitons?")
if rsp == "import":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")

rsp = question_with_response("What command defines a funciton?")
if rsp == "def":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")

rsp = question_with_response("Which command prints a specified messge on the screen?")
if rsp == "print":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")
    
rsp = question_with_response("Which command helps differentiate right from wrong?")
if rsp == "if":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")
    
rsp = question_with_response("Which command returns input from the user?")
if rsp == "return":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")
    
rsp = question_with_response("A collection of characters is called ____?")
if rsp == "string":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")
  
print(getpass.getuser() + " you scored " + str("{:.2%}".format(correct/6)))