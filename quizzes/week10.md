# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A set of signe used to identify and refer to objects of a particular kind. A namespace ensures that all of a given set of objects have unique names so that they can be easily identified.

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Struct is a composite data type declaration that defines a physically grouped list of variables under one name in a block of memory.
Class is a user-defined type or data structure declared with keyword class that has data and functions.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Add void onto the class. This makes it return an instance.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Start is the function name.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The request will return a string and that string is vroooom
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract prevenets another object being created.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual allows the class to be overriden for another class to append onto it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public,
Protected,
Internal,
and Public Internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The only class that can access it is the class in which it is declared private. 
```