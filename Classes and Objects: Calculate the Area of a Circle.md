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
```
from math import pi
r=int(input())
class cse:
   def mech(self,r):
      area=pi*r**2
      return print(f"Area of circle with radius {r} is",area)
obj=cse()
obj.mech(r)
      
   

```

## Output
<img width="1563" height="148" alt="image" src="https://github.com/user-attachments/assets/9f742ed8-7819-42a8-8f5d-80275e9a427c" />


## Result
Thus,To write a Python program that calculates the **area of a circle** based on the radius provided by the user is executed successfully.
