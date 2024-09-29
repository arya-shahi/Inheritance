# Inheritance
Experiment 14

## Aim
To understand the concept of inheritance.

## Theory
Inheritance in C++ allows a derived class to inherit properties and methods from a base class, promoting code reuse and a hierarchical class structure. This  promotes code reusability and establishes a hierarchical relationship between classes.

### Types of Inheritance
1. **Single Inheritance:** One derived class from one base class.
2. **Multiple Inheritance:** One derived class from multiple base classes.
 ```cpp
class Base1 {};
class Base2 {};
class Derived : public Base1, public Base2 {};
```
4. **Multilevel Inheritance:** A class derived from another derived class.
```cpp
class Base {};
class Derived1 : public Base {};
class Derived2 : public Derived1 {};
```
6. **Hierarchical Inheritance:** Multiple derived classes from one base class.
```cpp
class Base {};
class Derived1 : public Base {};
class Derived2 : public Base {};
```

## Algorithms
### Multiple Inheritance
1. **Define `Vehicle`:** Public member `company` = "Ford"; method `type()` = "Mustang".
2. **Define `Specs`:** Public member `mileage` = "8 kmph"; method `colour()` = "Grey".
3. **Define `Car`:** Inherits from `Vehicle` and `Specs`; public member `seater` = "4 seater".
4. **Main:** Create `Car` object `f2`, invoke methods and display members.

### Multilevel Inheritance
1. **Define `Food`:** Public member `cuisine` = "Indian"; method `type()` = "Asian".
2. **Define `Dish`:** Inherits from `Food`; member `dish` = "Biriyani".
3. **Define `Restaurant`:** Inherits from `Dish`; member `name` = "Spice Kitchen".
4. **Main:** Create `Restaurant` object `myRestaurant`, display members and invoke method.

### Hierarchical Inheritance
1. **Define `Jeans`:** Public array `type` with "Bootcut", "WideLeg", "Skinny"; method `brand()` = "Brand: H&M - &Denim".
2. **Define subclasses:** `Bootcut`, `WL`, `Skinny`, each with a public member `color`.
3. **Main:** Create objects `j1`, `j2`, `j3`; display type, color, and invoke `brand()`.

4. **End**

## Conclusion
In this experiment types of inheritance were studied 
