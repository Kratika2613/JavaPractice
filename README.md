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
Question1)
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
