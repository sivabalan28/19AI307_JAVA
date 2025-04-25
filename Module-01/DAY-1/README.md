# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To write a program to print the area of two rectangles having sides length, breath by creating a class named 'Rectangle'.

## ALGORITHM :
1. Start the program.
2. Import the Scanner class from the java.util package for input.
3. Define a class named Rectangle.
4. Inside the class, declare three integer variables: length, breath, and area.
5. Inside the main method:
6. Create two objects: obj1 and obj2 of class Rectangle.
7. Create a Scanner object to read input from the user.
8. Read the length and breath for obj1 using user input.
9. Read the length and breath for obj2 using user input.
10. Calculate the area of both rectangles using the formula length * breath.
11. Print the areas with a description.
12.  End the program.



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Sivabalan S
RegisterNumber: 212222240100
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Rectangle
{
    int length;
    int breath;
    int area;
    public static void main(String[] args)
    {
      {
        Rectangle obj1= new Rectangle();
        Rectangle obj2=new Rectangle();
        Scanner a= new Scanner(System.in);
        obj1.length=a.nextInt();
        obj1.breath=a.nextInt();
        obj2.length=a.nextInt();
        obj2.breath=a.nextInt();
        obj1.area=(obj1.length*obj1.breath);
        System.out.println("Area of Rectangle with side 4 and 5 is "+obj1.area);
        obj2.area=(obj2.length*obj2.breath);
        System.out.println("Area of Rectangle with side 5 and 8 is "+obj2.area);
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/f2e51430-7afe-46d9-9f77-061f70b3ce21)



## RESULT:
Thus, the program successfully creates a class named 'Rectangle' with integer variables 'length', 'breath', and 'area'.
