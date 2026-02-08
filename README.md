# Stationary-Shop
## Problem Description:
A python program to generate a list with just 4 products - A4 sheets, pens, pencils, and erasers and get the price of the items from the distributer(user) for a stationary shop

### Python Program
```
a4_cost-float(input("Cost of A4sheet: \n"))
pen_cost-float(input("Cost of pen:\n"))
pencil_cost-float(input("Cost of pencil:\n"))
eraser_cost-float(input("Cost of eraser:\n"))
if a4_cost<0 or pen_cost<0 or pencil_cost<0 or eraser_cost<0:
    print("Invalid input")
else:
  print("Item Details")
  print(f"A4sheet:{a4_cost:.2f}")
  print(f"Pen: {pen_cost:.2f}")
  print(f"Pencil:{pencil_cost:.2f}")
  print(f"Eraser: {eraser_cost:.2f}")
```
