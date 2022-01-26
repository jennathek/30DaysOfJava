# Calculating Area of Circle

***

1. Class Circle


  

2. Class Main

```java
    Scanner input = new Scanner(System.in);

    System.out.print("Enter the radius of a circle: ");
    double radius = input.nextDouble();

    input.close();
```
    
  By creating Scanner object for input, the users can input any radius(datatype double) after they are asked to enter the radius of a circle.
    
```java
    Circle circle1 = new Circle(radius);
    
    System.out.println("Area is " + circle1.getArea());
```
  This Circle object will pass the radius that user input into the getter(getRadius).
  And it is going to print the exact Area of the circle since the getter 'getArea' is calculated with the radius that user input. 
  

    

    

