# 🐍 6E Python OOP: Polymorphism with Classes
## Developed by : Srinithi muthukumar
## Register No. : 212224240161
## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.


## 💻 Program :
```
class Beans:
    def type(self):
        print("Vegetable")
    def color(self):
        print("Green")

class Mango:
    def type(self):
        print("Fruit")
    def color(self):
        print("Yellow")

def func(obj):
    obj.type()
    obj.color()

obj1 = Beans()
obj2 = Mango()

func(obj1)
func(obj2)

```
## Output :

<img width="1181" height="342" alt="image" src="https://github.com/user-attachments/assets/1d641c5c-bb4d-4345-bae5-c60a07f78d55" />

## Result :

The program successfully demonstrates polymorphism in Python OOP by using a generic function that works with different classes (Beans and Mango) and calls their respective methods.
