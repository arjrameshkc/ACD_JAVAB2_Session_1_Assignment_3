# ACD_JAVAB2_Session_1_Assignment_3

package com.session1.pack;
import java.util.Scanner;

public class SwapingTwoNumbers {

	public static void main(String[] args) {
		// TODO Auto-generated method stub		
		int x,y;
		Scanner scan = new Scanner(System.in);
		System.out.println("Before Swapping values");
		System.out.println("Enter value of X" );
		x =scan.nextInt();
	    System.out.println("Enter value of Y");
	    y=scan.nextInt();
	    x=x+y;
		y=x-y;
		x=x-y; 	 
		System.out.println("after Swapping values");
		System.out.println("Swap after value of X:" +x);
		System.out.println("Swap after value of Y:" +y);
		scan.close();
	   
	}

}
