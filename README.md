# lab3BeeversThomas
makin loopdy doops

//While Loop
Console.BackgroundColor = ConsoleColor.Black;
while (true)
{
    Console.WriteLine("pick a whole number between 10 and 99, if you wish to leave, type EXIT");
    string usertext = (Console.ReadLine());

    if (usertext == "EXIT")
    {
        Console.WriteLine("Good Bye!");
        Console.BackgroundColor = ConsoleColor.Black;
        break;
    }


    int usernumber = Convert.ToInt32(usertext);

    if (usernumber >= 99 || usernumber <= 10)

    {
        Console.WriteLine("invalid input, please try again");
   continue;
    }

    if (usernumber % 23 == 0 )
    {
        Console.BackgroundColor = ConsoleColor.Green;
    }

    else
    {
        Console.BackgroundColor = ConsoleColor.Red;
    }

}
Console.BackgroundColor = ConsoleColor.Black;


//Do While loop


do
{
    Console.BackgroundColor = ConsoleColor.Black;
    Console.WriteLine("pick a number between 10 and 99. Again, if you wish to leave type EXIT. ");
    string usertext = Console.ReadLine();

    if (usertext == "EXIT")
    {
        Console.WriteLine("Good Bye! ");
        Console.BackgroundColor = ConsoleColor.Black;
        break;
    }

    int usernumber = Convert.ToInt32(usertext);

    if (usernumber >= 99 || usernumber <= 10)
    {
        Console.WriteLine("number is too high, please try again. ");
   continue;
    }

    if (usernumber % 34 == 0 )
    {
        Console.BackgroundColor = ConsoleColor.Green;
        Console.WriteLine("that number is devisable by 34. Great job! ");
    }

else
    {
        Console.BackgroundColor = ConsoleColor.Red;
        Console.WriteLine("this number is not divsiable by 34, try again. ");
    }
}
while (true);

//FOR LOOP

for (bool loop = true; loop = true;)
{ Console.BackgroundColor = ConsoleColor.Black;
    Console.WriteLine("pick a number between 10 and 99. Again, if you wish to leave type EXIT. ");
    string usertext = Console.ReadLine();

 if (usertext == "EXIT")
    {
        Console.WriteLine("Good Bye! ");
        Console.BackgroundColor = ConsoleColor.Black;
        break;
    }

    int usernumber = Convert.ToInt32(usertext);

    if (usernumber >= 99 || usernumber <= 10)
    {
        Console.WriteLine("number is too high, please try again. ");
    continue;
    }

    if (usernumber %33 == 0)
    {
        Console.BackgroundColor = ConsoleColor.Green;
        Console.WriteLine("that number is devisable by 33. Great job! ");
    }

else
    {
        Console.BackgroundColor = ConsoleColor.Red;
        Console.WriteLine("this number is not divsiable by 33, try again. ");
    }

}
Console.BackgroundColor = ConsoleColor.Black; 
