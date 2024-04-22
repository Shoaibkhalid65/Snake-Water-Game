import random

def check(comp, user):
    if (comp==user):
        return 0
    if (comp==1 and user==0):
        return -1
    if (comp==1 and user==2):
        return -1
    if (comp==2 and user==0):
        return -1
    else:
        return 1
comp=random.randint(0, 2)
user=int(input("Enter:\n0 for Snake\n1 for Water\n2 for Gun\n"))
a=check(comp, user)
print("You select:",user)
print("Computer select:",comp)

if (a == 0):
    print("Game is draw","\U0001F609")
elif (a == -1):
    print("You loose game","\U0001F617")
elif (a==1):
    print("You won game","\U0001F603")
