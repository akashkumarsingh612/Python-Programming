## Guess The Number Program in PYTHON
In this Program, you have to guess the number which is assigned in the Program 
and you'll have limited attempts : 


### Source_Code ->


```markdown
Syntax highlighted code block

#Program : Guess the Number


num = 15
print("You have 8 attempts so let's guess the Correct Number !")
attempts = 8

for i in range(8):
    no_of_attmepts_left = attempts
    print("No. of attempts left ->", attempts)
    i = int(input("Guess the Number : "))
    if i == num:
        print("Congrats! You Guess the Correct no.")
        break
    elif i < num:
        print(i, "is lesser than the Correct no. Try Again!")
    else :
        print(i, "is greater than the Correct no. Try Again!")
    if no_of_attmepts_left == 1:
        print("No more attempts left! if you want to try again then rerun the Program :)")
    attempts = attempts - 1



# Code Written by CodinGuy aka AKASH
# Website : learntocode404.blogspot.com
