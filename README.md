[EgarsLegendaryPuzzle.py](https://github.com/user-attachments/files/23322612/EgarsLegendaryPuzzle.py)
import webbrowser
#All puzzle methods
def puzzle():
    code = float(input("Enter the answer to the puzzle "))
def puzzle2():
    x = float(input("Do you have an asnswer? enter it here "))
def puzzle3():
    print("hmmm..... if a = 1...")
    p = float(input("Enter the code "))
    if p == 20192021:
        print("wow you're a sharp kookie! what did you think of the st0p sign?")
        print("It wasn't easy to figure out how to make my own bamn website")
        print("maybe you've had anough of it for now?")
        puzzle4()
    else:
        puzzle3()
    
def puzzle4():
    u = input()
    if u == "code":
        print("Wow! you caught my misspellings?? very impressive")
        print("Do you ever wonder when this puzzle will end?")
        print("and what if you need something else from the website?")
        print("I hope you didn't close it....")
        print("just in case.....")
        webbrowser.open("https://a37nsw872e99er.my.canva.site/diff-site000code-orange-you-glad")
        print("you never know. Maybe you DONT need it.")
        puzzle5()
    else:
        puzzle4()
def puzzle5():
    w = input()
    if w == "orange you glad":
        print("...")
        print(".......")
        print("...............")
        print("")
        print("")
        print("")
        print("")
        print("ORANGE YOU GLAD TO MEET ME")
        print("okay that was lame")
        print("even I can admit it")
        print("good thing you checked that url")
        print("this is the last one....")
        print("It'll be the hardest one....")
        print("I wish you luck...")
        puzzle6()
    else:
        puzzle5()


def puzzle6():
    t = input("")
    if t == "Julius Caesar made the leap year":
        print("Congrats")
        print("Thank you for playing")
        end()
    else:
        puzzle6()

def end():
    print("Made by Egar")
    y = input("Input x to exit ")
    if y == "x":
        exit()
    else:
        end()
    
#This is the beginning/what the player will see first.
#lowkey puzzle 1 :O
print("Enter the 4 digit code.")
print("The first digit is a prime number.")
print("The second digit is double the first")
print("The third digit is 3 greater than the smallest prime number")
print("The fourth digit is the sum of the first two, 9")
code = float(input("Enter the answer to the puzzle "))
if code == 3659:
    webbrowser.open("https://a37nsw872e99er.my.canva.site/")
else:
    puzzle()

#puzzle 2 beginning and into puzzle 3
x = float(input("Do you have an asnswer? enter it here "))
if x == 3787299:
    print("well done. You solved your second puzzle.")
    print("you're one step closer to completing this challenge.")
    print("find another clue on the website. ")
    puzzle3()
else:
    puzzle2()
