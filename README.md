#java program for factorial

#import essential header files
import java.util.Scanner;
 
class Factorial
{
   public static void main(String args[])
   {
      int n, c, fact = 1;
 
      System.out.println("Enter an integer to calculate it's factorial");
      Scanner in = new Scanner(System.in);
 
      n = in.nextInt();
 
      if ( n < 0 )
         System.out.println("Number should be non-negative.");
      else
      {
      #calculate factorial
         for ( c = 1 ; c <= n ; c++ )
            fact = fact*c;
      #display result
         System.out.println("Factorial of "+n+" is = "+fact);
      }
   }
}
