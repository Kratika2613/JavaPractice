Question 1)
Sum of two number a & b through user input ?

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {
    Scanner hell = new Scanner (System.in);
    
      System.out.print ("Enter value of a:");
      int a = hell.nextInt ();  //Here a is 20
      
      System.out.print ("Enter value of b:");
      int b = hell.nextInt ();  //Here b is 10
      
      int sum = a + b;
      System.out.print("The sum of a & b is:");
      
      System.out.println (sum);

  }
}
Output:-
The sum of two number is : 30

Question2)
In a program,input 3 numbers:A,B and C.You havet oout put the average of these 3 numbers.
import java.util.Scanner;
public class side
{
    public static void main(String[]args)
    {
        Scanner sc=new Scanner(System.in);
        float a=sc.nextFloat();
        float b=sc.nextFloat();
        float c=sc.nextFloat();
        float avg=(a+b+c)/3;
        System.out.println(avg);
    }
}

Question3)
Enter cost of 3items from the user(using float data type)-a pencil,a pen and an eraser. You have to output the total cost of the items back to the user as their bill.

import java.util.Scanner;
public class side
{
    public static void main(String[]args)
    {
        try (Scanner sc = new Scanner(System.in)) {
            float a=sc.nextFloat();
            float b=sc.nextFloat();
            float c=sc.nextFloat();
            float avg=(a+b+c)*18/100+20;
            System.out.println(avg);
        }
    }
}
