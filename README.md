import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Ideone
{
	public static void main (String[] args) throws java.lang.Exception
	{
		int n;
		Scanner s=new Scanner(System.in);
		System.out.println("enter a number:");
		n=s.nextInt();
		if(n%2==0)
		{
			System.out.println("the given number "+n+" even");
		}
		else 
		{
			System.out.println("the given number "+n+" odd");
		}
	
	}
}
