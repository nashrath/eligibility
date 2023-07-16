# eligibility
name=input("Enter Name")
age=int(input("Enter Age"))
if (age < 18):
  print("You are a minor")
elif (age >= 18 && age < 65 ):
  print("You are an adult")
else:
  print("You are a senior")
