# X-Team 20 Style Guide

A clean segment of code includes well commented lines along with appropriate spacing. This allows team members to easily and quickly understand code that they did not construct.

## Naming conventions

All the naming convetions should be descriptive in the right matter. It should be concise. 

### Examples
* interfaces
  * The name should start with upper case letter nad must be a comprehensable word e.x. Comparable 
* classes
  * The name should start with upper case letter nad must be clear that it's abstract construct e.x. ListADT
* exception types
  * Each word must be concantenated together and the beginning of each word should be capitalized e.x DuplicateKeyException()
* fields
  * Must be descriptive and a phrase or word. First letter must be lower case e.x heightOfTree
* methods
  * Must be descriptive and a phrase or word. First letter must be lower case e.x getHeight
* parameters
  * Must be descriptive and a phrase or word. First letter must be lower case e.x leftChild
* local variables
  * Must be descriptive and a phrase or word. First letter must be lower case e.x rightChild
* instance constants
  * Must be all capital letter and a descriptive phrase or word. Words are saparated by underscore e.x NUMBER_OF_CHILDREN
* class constants
  * Must be all capital letter and a descriptive phrase or word. Words are saparated by underscore e.x NUMBER_OF_CHILDREN
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
