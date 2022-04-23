# else-statement-
using System;
using System.Linq;
using System.Collections.Generic;
namespace HelloWorld

{
    public class Program 
    {
        public static void Main()
        {
			int age;
			Console.WriteLine("Entet age of candidate");
			age=Convert.ToInt32(Console.ReadLine());
			
			if(age>=18)
			{
			    Console.WriteLine("Eligible for vote");
			}
			else
			{
	         	Console.WriteLine("Not eligible for vote");
			}
        }
    }
}
