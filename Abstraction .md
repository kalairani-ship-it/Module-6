# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def calculate_area(self):
        pass


class Rectangle(Shape):
    def __init__(self):
        self.length = 5
        self.breadth = 3
    def calculate_area(self):
        print("Rectangle Area:", self.length * self.breadth)


class Circle(Shape):
    def __init__(self):
        self.radius = 4
    def calculate_area(self):
        print("Circle Area:", 3.14 * self.radius * self.radius)


r = Rectangle()
r.calculate_area()

c = Circle()
c.calculate_area()
## Output
<img width="370" height="237" alt="image" src="https://github.com/user-attachments/assets/361f616a-c3ad-4acd-b6e2-b3cee46f00cd" />

## Result
Thus, the code was implemented successfully.
