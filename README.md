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
