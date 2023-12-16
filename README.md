2.Write a program that given number is positive or negative ?
import java.util.Scanner;
public class Main{
public static void main(String[] args) 
    {
        int n=27;
        Scanner Object= new Scanner(System.in);
//          System.out.print("Enter the number");
        if(n > 0)
        {
            System.out.println("The given number is Positive");
        }
        else if(n < 0)
        {
            System.out.println("The given number is Negative");
        }
        else
        {
            System.out.println("The given number is neither Positive nor Negative ");
        }
    }
}
