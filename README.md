//import stuff here!

//Your code here
import java.util.Scanner;

public class Program6 {
    public static void main(String[] args) {
        // Define a constant for pi
        final double PI = 3.14159;

        // Create a Scanner object to get user input
        Scanner scanner = new Scanner(System.in);

        // Get the radius from the user
        System.out.print("Enter the radius: ");
        double radius = scanner.nextDouble();

        // Calculate the diameter
        double diameter = 2 * radius;

        // Calculate the area
        double area = PI * radius * radius;

        // Calculate the circumference
        double circumference = 2 * PI * radius;

        // Print out the results
        System.out.printf("The Radius of the circle = %.3f\n", radius);
        System.out.printf("The Diameter of the circle = %.3f\n", diameter);
        System.out.printf("The Area of the circle = %.3f\n", area);
        System.out.printf("The Circumference of the circle = %.3f\n", circumference);

      //
    }
}

//Paste console output below:
/*
Enter the radius: 45
The Radius of the circle = 45.000
The Diameter of the circle = 90.000
The Area of the circle = 6361.720
The Circumference of the circle = 282.743

*/
