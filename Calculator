def add(x,y): #for addition
  return x+y
def subtract(x,y): #for subtraction
  return x-y
def multiply(x,y): #for multiplication
  return x*y
def divison(x,y): #for divison
  return x/y
  
print("Select Operation:")
print("1.Addition")
print("2.Subtraction")
print("3.Multiplication")
print("4.Division")

while True:
  choice=input("Enter Choice(1/2/3/4): ") #taking choice from the user
  
  if choice in("1","2","3","4"):
    try:
      x=int(input("Enter the first number: "))  #taking the input numbers from the user
      y=int(input("Enter the second number: "))
    except:
      print("Invalid Input..Try Again!!")
      continue
    
    if choice=="1":
      print(x,"+",y,"=",add(x,y))
    elif choice=="2":
      print(x,"-",y,"=",subtract(x,y))
    elif choice=="3":
      print(x,"*",y,"=",multiply(x,y))
    elif choice=="4":
      print(x,"/",y,"=",divison(x,y))
      
    repeat_calculation=input("Do you want to calculate again?(yes/no)") #asking the user to repeat the calculation again or not
    if repeat_calculation=="no":
      break
  else:
  print("Invalid Input")
  
      


  
  
  
  
  
