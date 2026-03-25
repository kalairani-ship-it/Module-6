# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class Rectangle:
    def __init__(self):
        self.__length = 10
        self.__breadth = 5
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

obj = Rectangle()
## Output
<img width="382" height="243" alt="Screenshot 2026-03-25 212514" src="https://github.com/user-attachments/assets/715e2234-7b3f-42a9-9355-540b469db9d4" />

## Result
Thus, the code was executed successfully.
