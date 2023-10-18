## wow sugoi-desu
## even more sugoi link text 
### code?
```py 
import random 

repeat = True

while repeat:
    number = random.randint(1, 100)
    guess = 0 
    tries = 0


    while guess != number:
        if guess > number:
            tries += 1
            print("Guess lower number")
        else:
            tries += 1
            print("Guess higher number")

        guess = int(input("Guess the number boi: "))
    else:
        print(f"YOU GUESSED IT YIPEE!!!! It only took you {tries} tries")


    response = input("wanna try again? y/n: ")
    if response == "y":
        repeat = True
    elif response == "n":
        repeat = False
        print("GG bro")
    else:
        repeat = False
        print("You didnt write y/n but still GG")

```
