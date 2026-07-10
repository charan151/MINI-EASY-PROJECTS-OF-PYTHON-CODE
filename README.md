# MINI-EASY-PROJECTS-OF-PYTHON-CODE
# THIS ARE SOME MINI PROJECTS OF PYTHON
#basic caluculator
a = int(input("give first number:"))
b = int(input("give second number:"))
operation = input("give operator:")
if operation == "+":
    print(a+b)
elif operation == "-":
    print(a-b)
elif operation == "*":
    print(a*b)
elif operation == "/":
    print(a/b)
elif operation == "**":
    print(a**b)
elif operation == "//":
    print(a//b)
elif operation == "%":
    print(a//b)
else: print("operation is not included")

#age caluculator
birth_year=int(input('enter your birth year: '))
current_year=int(input('enter the present or ending year: '))
print("your age is: ",current_year-birth_year)

#this is my own
#money currency converter
currency_type=input('give me the type of currency: ')
amount=int(input("give me the amount to convert: "))
convert=input("give me the type of currency to convert in: ")
if currency_type.lower()=='usd':
  if convert.lower()=='inr':
         print(amount*94.33,'inr')
  elif convert.lower()=='euro':
         print(amount*0.87,'euro')
  else: print('invalid type')
elif currency_type.lower()=='inr':
     if convert.lower()=='usd':
         print(amount*0.011,'usd')
     elif convert.lower()=='euro':
         print(amount*0.0093,'euro')
     else: print('invaild type')
elif currency_type.lower()=='euro':
     if convert.lower()=='usd':
         print(amount*1.15,'usd')
     elif convert.lower()=='inr':
         print(amount*108.34,'inr')
     else: print('invaild type')
else: print("type is not inculded in this version")
#this code is working in python compiller but not in vs code

#temp converter
temp_type=input('give me the type of temp: ')
temp_value=int(input('give me the value of temp: '))
convert=input('give me the type of temp to convert: ')
if temp_type.lower()=='c':
  if convert.lower()=='f':
    print((temp_value*(9/5))+32,'F')
  elif convert.lower()=='k':
    print(temp_value+273.15,'K')
  else: print('invaild type')
elif temp_type.lower()=='k':
   if convert.lower()=='c':
     print(temp_value-273.15,'C')
   elif convert.lower()=='f':
      print((temp_value-273.15)*9/5+32,'F')
   else: print('invaild type')
elif temp_type.lower()=='f':
  if convert.lower()=='k':
    print((temp_value-32)*5/9+273.15)
  elif convert.lower()=='c':
    print((temp_value-32)*5/9)
  else: print('invaild type')
else: print('invaild type')
#good working
