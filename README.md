# Calculate-BMI
You can Calculate your BMI Through This Code. 
height = float(input("Enter your height(in Metres): "))
weight = float(input("Enter your weight(in Kilograms): "))
bmi = float(weight / height ** 2)
print("Your BMI is: ", bmi)
if bmi <= 18.5:
    print("You are Underweight")
elif bmi > 18.5 and bmi < 24.9:
    print("You have a normal weight")
elif bmi > 25 and bmi < 29.9:
    print("You are overweight")
elif bmi > 30 and bmi < 39.9:
    print("You are Obese")
elif bmi > 40:
    print("You are morbidly obese")
else:
    print("there is an error with your input")
    print("please check the numbers you have entered")
