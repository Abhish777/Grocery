print("Hello there")
print("Welcome to the store")
print("What u want to purchase!")
print("Please select the options from the list")
print("L: list of items")
global orange
global apple
global mango

orange = 10
apple = 5
mango = 6

userIn = input()

if userIn == "L":
    print("Choose from the list")
    print("We have ", "orange: ", orange, "apple: ", apple, "mango: ", mango,)
    print("select the item u want to choose e.g orange, apple, mango")

    userIn = input("")
if userIn == "orange":
    print("How many", userIn)
    buythis = int(input())
    orange = int(orange-buythis)
    print("Thank you, now we have, ", orange, userIn)

elif userIn == "apple":
    print("How many", userIn)
    buythis = int(input())
    apple = int(apple-buythis)
    print("Thank you, now we have, ", apple, userIn)

elif userIn == "mango":
    print("How many", userIn)
    buythis = int(input())
    mango = int(mango-buythis)
    print("Thank you, now we have, ", mango, userIn)

else:
    print("Didn't not select L")

