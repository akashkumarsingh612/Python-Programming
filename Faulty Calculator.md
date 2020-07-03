## Faulty Calculator Program in PYTHON
In this program we'll create a faulty calculator which executes all inputs correctly except these ones: 
 -> 56+9 = 77                
 -> 45*3 = 555            
 -> 56/6 = 4


### Source_Code ->


```markdown
Syntax highlighted code block


#Program : Faulty Calculator

num1 = float(input("Enter First Operand -> "))
opr = input("Enter Operator -> ")
num2 = float(input("Enter Second Operand -> "))

if opr == "+":
    if num1 == 56 and num2 == 9:
        print("56 + 9 = 77")
    else:
        print(num1, '+', num2, '=', num1+num2)
        
elif opr == "*":
    if num1 == 45 and num2 == 3:
        print("45 * 3 = 555")
    else:
        print(num1, '*', num2, "=", num1*num2)
        
elif opr == "/":
    if num1 == 56 and num2 == 6:
        print("56 / 6 = 4")
    else:
        print(num1, '/', num2, '=', num1/num2)
        
elif opr == "-":
    print(num1, '-', num2, '=', num1-num2)
else :
    print("Plese enter valid Integer or operator! ")




# Code Written by CodinGuy aka AKASH
# Website -> learntocode404.blogspot.com
