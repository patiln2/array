using System;
namespace array
{
    public class Array
    {
        public static void Main() 
        {
        int num;
           int [] a={1,2,3,4,5,6};
           Console.WriteLine("enter any number");
           num=Convert.ToInt32(Console.ReadLine());
           if(num==a[0])
          {          	Console.WriteLine("true");
          }
          else	if(num==a[1])
          {         	Console.WriteLine("true");
          }
          else	if(num==a[2])
          	{          		Console.WriteLine("true");
          	
          
          	}
          else	if(num==a[3])
          	{                Console.WriteLine("true");
          	}
          else	if(num==a[4])
          	{                Console.WriteLine("true");
          	}
          	else if(num==a[5])
          	{                Console.WriteLine("true");
          }
          
         else
          {
          Console.WriteLine("false");
          }
       }
    }  }
