height = float(input(1.55))
weight = int(input(108))

bmi = weight / (height * height)
if bmi < 18.5:
   print(f" Your BMI is {bmi}, you are underweight.")
elif bmi < 25:
   print(f"Your BMI is {bmi}, you have a normal weight.")
elif bmi < 30:
   print(f"Your BMI is {bmi}, your are slightly overweight.")
elif bmi < 35:
  print(f"Your BMI is {bmi}, you are clinically obese.")
