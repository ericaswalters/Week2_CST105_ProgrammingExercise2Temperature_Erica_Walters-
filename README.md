# Week2_CST105_ProgrammingExercise2_Erica_Walters-
/* This program converts farenheit temperature to celcius 
 * This program converts celcius temperature to farenheit temperature
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/** Program: Temperature Conversion
 * File: TemperatureConversion.java
 * Summary: Converts user input temperature from degrees-f (farenheit) to degrees-C (celcius) and vice versa.
 * Author: Erica Walters
 * Date: November 18, 2018
 */
import java.util.Scanner;

public class TemperatureConversion {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Enter 1 to convert temperature from farenheit to celcius or ");
        System.out.print("Enter 2 to convert temperature from celcius to farenheit");
        int choice = input.nextInt();

        {
                
        System.out.print("Enter temperature in Farenheit: ");
        double farenheit = input.nextDouble();
        
        //convert farenheit temperature to celcius temperature
        double celcius = (farenheit - 32) * (5.0/9);
        
        System.out.println("Temperature farenheit " + farenheit + " is " + celcius + "in celcius");}

        {
        
        System.out.print("Enter temperature in celcius: ");
        double celcius = input.nextDouble();
        
        //convert celcius temperature to farenheit temperature
        double farenheit = celcius * (9.0/5) + 32;
        
        System.out.println("Temperature celcius " + celcius + " is " + farenheit + "in farenheit");}
    }
    }

