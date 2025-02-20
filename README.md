print("Welcome to the rollercoaster!")
height = int(input("What is your height in cm? "))
Bill = 0

if height >= 120:
    print ("you can ride the rollercoaster")
    age=int(input("what is your age?"))
    if age <=12:
        Bill=5
        print ("Child tickets are $5.")
    elif age <=18:
        Bill=7
        print ("Youth tickets are $7.")
    else:
        Bill=12
        print("Adult tickets are $12.")
# Vikesh
