# Factorial


import java.util.Scanner;
 
class Factorial
{
   public static void main(String args[])
   {
      int n, c, fact = 1,i,sum=0;
 
      System.out.println("Enter an integer to calculate it's factorial");
      Scanner in = new Scanner(System.in);
 
      n = in.nextInt();
 
      if ( n < 0 )
         System.out.println("Number should be non-negative.");
      else
      {
         for ( c = 1 ; c <= n ; c++ )
            fact = fact*c;
 
         System.out.println("Factorial of "+n+" is = "+fact);
      }
      System.out.pritln("sum of nos.upto given no.:");
      for(i=1;i<=n;i++)
          sum+=i;
      System.out.println("Sum is:"+sum);
   }
}
