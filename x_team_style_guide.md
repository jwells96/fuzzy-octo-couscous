# X-Team 20 Style Guide

A clean segment of code includes well commented lines along with appropriate spacing. This allows team members to easily and quickly understand code that they did not construct.

## Naming conventions

All the naming convetions should be descriptive in the right matter. It should be concise. 

### Examples
* interfaces
 * 
* classes
* exception types
* fields
* methods
* parameters
* local variables
* instance constants
* class constants

## Commenting style for public and private members of a class or interface:

<brief statement of your team's commenting style>

### Examples

* classes
```Java
public class exampleClass {

}
```
* fields
```Java
int firstInt = 0;
String emptyStr = "";
```
* constructors
```Java
public exampleClass(int firstInt, String emptyStr) {
}
```
* methods
```Java
public callStack(int input) {
}
```
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  ``` Java
  
  if(date == 1) {
  }
  else if(date <= 5) {
  }
  else {
  }
  ```
  * switch statement
   ``` Java
    switch (month) {
        case 2:
            daysInMonth = 28;
            break;
        case 4:
        case 6:
        case 9:
        case 11:
            daysInMonth = 28;
            break;
        default:
            daysInMonth = 31;
            break;
    }
    ```
  * while loops
  ```Java
  while(true) {
  }
  ```
  * for loops
  ```Java
  for(int i = 0; i < MAX; i++) {
  }
  ```
  * enhanced for loops
  ```Java
  for (Penguin p : it) {
  }
  ```
