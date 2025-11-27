# 🐟 6C Method Overriding-Fish and Shark Class Inheritance in Python
## Developed by : Srinithi muthukumar
## Register No. : 212224240161
## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM :
```
class A:
    def __init__(self, a):
        self.a = a

    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"

ob1 = A(5)
ob2 = A(10)

print(ob1 < ob2)
```
## OUTPUT : 

<img width="1177" height="268" alt="image" src="https://github.com/user-attachments/assets/0d4b9f0a-2689-4719-a98e-b7cdc222abd3" />


## RESULT :

The program successfully demonstrates operator overloading in Python by overriding the less than (<) operator using the lt() method.
