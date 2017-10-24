# area-and-circumference
First full program - calculate area and circumference of a circle using an input



The program attached Circle-test.java is written out below:

package edu.cscc;
import java.util.Scanner;

// Adeline Davis - Calculate a circle's area and circumference

public class Main {

    private static Scanner input = new Scanner(System.in);

    public static void main(String[] args) {
        double radius;
        double area;
        double perimeter;

        Scanner userInput = new Scanner (System.in);
        String name = "";
            System.out.print("Please enter a radius.");
            radius = input.nextDouble();
            area = Math.PI * radius * radius;
            System.out.println("The area of a circle with a radius of " + radius + " is " + area);
            perimeter = 2 * Math.PI * radius;
            System.out.println("The circumference of a circle with a radius of " + radius + " is " + perimeter);
        }
    }
