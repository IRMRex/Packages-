import sys
import math   
import random    
def CAL():
    print("1) Addition 2) Subtraction 3) Multiplication 4) Division 5) ABS 6) SQRT 7) Random 8) Cancel")
    OPRAN = input("What operation would you like to do? ")
    if OPRAN == 7:
        RAND = random.randint(1,100000)
        print(RAND)
    NUM1 = int(input("Please input a number "))
    NUM2 = int(input("PLease input a number "))
    if OPRAN == "1":
        print(NUM1 + NUM2)
    elif OPRAN == "2":
        print(NUM1 - NUM2)
    elif OPRAN == "3":
        print(NUM1 * NUM2)
    elif OPRAN == "4":
        print(NUM1 / NUM2)
    elif OPRAN == "5":
        print(abs(NUM1))
        print(abs(NUM2))
    elif OPRAN == "8":
        sys.exit()
    elif OPRAN == "6":
        print(math.sqrt(NUM1))
        print(math.sqrt(NUM2))
    AC = input("Would you like to make another calculation? ")
    if AC == "Y" or AC == "y" or AC == "Yes" or AC == "yes":
        CAL()
    elif AC == "N" or AC == "n" or AC == "No" or AC == "no":
        sys.exit()
    else:
        CAL()
CAL()