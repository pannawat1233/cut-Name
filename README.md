/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.mavenproject7;
import java.util.Scanner;

/**
 *
 * @author PC
 */
public class Mavenproject7 {

    public static void main(String[] args) 
    {
        System.out.println("Enter you name");
        Scanner inputname = new Scanner(System.in);
        String name = inputname.nextLine();
       // Scanner inputlastname = new Scanner(System.in);
       // String lastname = inputlastname.nextLine();
       String[] nameParts = name.split(" ");
       if(nameParts.length >= 2)
       {
            String firestname = nameParts[0];
            String Lastname = nameParts[nameParts.length-1];
            System.out.println("FirestName"+" "+firestname);
            System.out.println("Lastname"+" "+Lastname);
       }
       else
       {
           System.out.println("Please enter you full name");
       }
    }
}
