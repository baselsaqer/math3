# math3
package basel;

import java.util.Scanner;

public class math2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.print("enter your number :");
		Scanner number = new Scanner(System.in);
		
		int a = number.nextInt();
		int b = number.nextInt();
		
		
		System.out.print("enter your math mark ");
		Scanner ma = new Scanner(System.in);
		char math = ma.next().charAt(0);
		
		switch (math) {
		case '+':
			System.out.print(a+b);
			break;
		case '-':
			System.out.print(a-b);
			break;
		case '*':
			System.out.print(a*b);
			break;
		case '/':
			System.out.print(a/b);
		break;
		
		
		
		
		
		
		}
		
	}

}
