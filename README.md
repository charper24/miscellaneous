# miscellaneous
simple miscellaneous projects class/personal

import java.util.Scanner;

public class CelsiusToFahrenheit {


   public static double celsiusToFahrenheit(double tempC) {
      final double celsiusConversion = 1.8;
      final double fahrenheitConstant = 32;
      double tempF = 0;
      
      tempF = (tempC*celsiusConversion) + fahrenheitConstant;
      
      
      return tempF;
   }

   public static void main (String [] args) {
      Scanner scnr = new Scanner(System.in);
      double tempF = 0.0;
      double tempC = 0.0;

      System.out.println("Enter temperature in Celsius: ");
      tempC = scnr.nextDouble();

       

      System.out.print("Fahrenheit: ");
      System.out.println(celsiusToFahrenheit(tempC));
      
      return;
   }
}
