// Java Program to Find Factorial of a Number
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

  
        System.out.print("Enter a number: ");
        int num = sc.nextInt();

        int factorial = 1;
        for(int i = 1; i <= num; i++) {
            factorial = factorial * i;
        }
        System.out.println("Factorial of " + num + " is " + factorial);

        sc.close();
    }
}
output:
Enter a number: 5
Factorial of 5 is 120
