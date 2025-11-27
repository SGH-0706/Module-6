# 🐍 6B Python OOP: Encapsulation with Private Members
## Developed by : Srinithi Muthukumar
## Register No. : 212224240161
## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

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

## 💻 Program : 

```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length      # private member
        self.__breadth = breadth    # private member
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)
rect = Rectangle(10, 5)

```

## Output :

<img width="1172" height="274" alt="image" src="https://github.com/user-attachments/assets/4e51952f-9260-4496-8a2e-894482270775" />

## Result : 

The program successfully demonstrates Encapsulation in Python by using private members __length and __breadth in the Rectangle class.
