using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace SoloLearn
{
	class Program
	{
		static void Main(string[] args)
		{
			int num;
			System.Console.WriteLine("enter dig");
			num=Console.ReadLine();
			if(num=>0)
{
			System.Console.WriteLine("positive ");
    
}
else {
    System.Console.WriteLine("negetive");
}
		}
	}
}
22222
Using System;

class Program
{
    public static void Main()
    {
        Console.WriteLine("Enter a string:");
        string  strname= Console.ReadLine();
        
        string uppercaseString = strname.ToUpper();
        
        Console.WriteLine("The string in uppercase is: " + uppercaseString);
    }
}
33333
Using System;

public class Program
{
    public static void Main(string[]args)
    {
        int[] numbers = new int[3];
        
        Console.WriteLine("Enter the first number:");
        numbers[0] = Convert.ToInt32(Console.ReadLine());
        
        Console.WriteLine("Enter the second number:");
        numbers[1] = Convert.ToInt32(Console.ReadLine());
        
        Console.WriteLine("Enter the third number:");
        numbers[2] = Convert.ToInt32(Console.ReadLine());
        
        Array.Sort(numbers);
        
        Console.WriteLine("The numbers in ascending order are:");
        
        foreach(int number in numbers)
        {
            Console.WriteLine(number);
        }
    }
}

