# Odd-Number
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Odd_Number
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());

            while (true)
            {
                n = Math.Abs(n);
                if (n % 2 != 0)
                {
                    break;
                }
                Console.WriteLine("Please write an odd number.");
                n = int.Parse(Console.ReadLine());
            }
            Console.WriteLine($"The number is: {n}");
        }
    }
}
