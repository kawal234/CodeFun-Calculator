# CodeFun-Calculator
print("Welcome to the CodeFun Calculator:")
num1 = int(input("Enter the first Number:"))
num2 = int(input("Enter the Second Number:"))
oper = input("Enter the Operator(+,-,*,/,//,**):")
if oper == "+":
  print("The Answer is:",num1+num2)
elif oper == "-":
  print("The Answer is:",num1-num2)
elif oper == "*":
  print("The Answer is:",num1*num2)
elif oper == "/":
  print("The Answer is:",num1/num2)
elif oper == "//":
  print("The Answer is:",num1//num2)
elif oper == "**":
  print("The Answer is:",num1**num2)

print("Thanks For Using Our Calculator.")
