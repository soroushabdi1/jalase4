1#import random                                       
input("Plz touch ENTER key to start the game")     
Enter 
number=random.randint(1,6)                       
dice=str(number)                       
while number==6:                                    
    print("Congradulation! you win a 6.")
    input("Plz touch ENTER again")
    number=random.randint(1,6)
    dice=dice+" => "+str(number)
print("")
print("Oooops! the number is: "+str(number))       
print("Game is over")
if len(dice)>1:
    print("Your number trail was: "+dice)
    
