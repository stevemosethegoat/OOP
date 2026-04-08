# My OOP Learning Journey 🚀

A documentation of how I learned Object-Oriented Programming (OOP) concepts, from basics to practical implementation.

## 📚 Why I Learned OOP

I wanted to write cleaner, more reusable, and organized code. OOP helps model real-world problems effectively by using classes and objects.

## 🗺️ Learning Path

### 1. Understanding the Basics
Started with the four fundamental pillars of OOP:

- **Encapsulation** → Bundling data and methods together, hiding internal details
- **Abstraction** → Showing only essential features, hiding complex implementation
- **Inheritance** → Creating child classes from parent classes (reusing code)
- **Polymorphism** → Same method name, different behaviors (method overriding/overloading)

### 2. Languages I Used
Practiced OOP in multiple languages to grasp universal concepts:
- **Python** (first) - beginner-friendly syntax
- **JavaScript** (second) - prototype-based OOP
- **Java** (third) - strict classical OOP

### 3. Projects I Built

| Project | Concepts Applied |
|---------|------------------|
| Bank Account System | Encapsulation, methods |
| Animal Sound Simulator | Inheritance, polymorphism |
| Library Management System | All 4 pillars + composition |
| Employee Payroll | Abstract classes, interfaces |

### 4. Key Code Examples

#### Class & Object (Python)
```python
class Car:
    def __init__(self, brand, model):
        self.brand = brand      # attribute
        self.model = model
    
    def start(self):            # method
        return f"{self.brand} {self.model} is starting"

my_car = Car("Toyota", "Camry")
print(my_car.start())
