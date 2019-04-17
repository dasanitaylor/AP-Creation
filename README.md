print("Hello! Welcome to Math Practice!")
choice = str(input("What do you want to practice? Addition, substraction, multiplication or divsion?"))
if choice == "addition":
    print("add")
#subtraction
subglossary ={
    "10-3":"7",
    "56-50":"6",
    "27-18":"9",
    "197-97":"100"
    }
for key,val in subglossary.items():
    choice = str(input("What do you want to practice? Addition, substraction, multiplication or divsion?"))
    if choice == "subtraction":
        firstprob= key
        print(key)
        answer= input("what is the answer?")
        if answer == val:
            print("correct")
        elif answer != val:
            print("go study")
