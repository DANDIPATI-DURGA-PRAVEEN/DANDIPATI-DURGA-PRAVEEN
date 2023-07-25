marks = int(input("Enter your marks: "))
if(marks >= 90):
    print("A+")
elif(80 <= marks <= 89):
    print("A")
elif(70 <= marks <= 79):
    print("B")
elif(60 <= marks <= 69):
    print("C")
elif(50 <= marks <= 59):
    print("D")
else:
    print("Fail")
