using System;


class DIPIKA Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("calculator");
       
        //ask the user to enter the first number
        // Type your username and press enter
        Console.WriteLine("Enter username:");
        string userName = Console.ReadLine();
        Console.Write("enter the amount:");
        int a = Convert.ToInt32(Console.ReadLine());

        //ask the user to enter the second number
        Console.Write("enter the amount spent:");
        int b = Convert.ToInt32(Console.ReadLine());
        int result = a - b;
        Console.WriteLine("Username is" + userName);
        Console.WriteLine("The remaining amount is " + result);
        
        Console.Read();
    }
}
