# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
      import math
      class cse:
          def mech(self,r):
              return math.pi*r**2
      circle=cse()
      try:
          r=int(input())
          area=circle.mech(r)
          print(f"Area of circle: {area:.2f}")
      except ValueError:
          print("Invalid input")


## Output
![image](https://github.com/user-attachments/assets/76c50814-ff04-4360-89b0-a032c08d5f7f)


## Result
Thus,the program has been execueted successfully.
