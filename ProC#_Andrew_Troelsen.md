### Pro C# by Andrew Troelsen
<hr>

##### Take aways

<hr>
```
// example code

class Program
{
    static void Main(string[] args)
    {
        // Display a simple message to the user.
        Console.WriteLine("***** My First C# App *****");
        Console.WriteLine("Hello World!");
        Console.WriteLine();
        // Wait for Enter key to be pressed before shutting down.
        Console.ReadLine();
    }
}
/*
Note:
    C# is a case-sensitive programming language, Therefore, Main is not the same as main, and headline is not the same as ReadLine. Be aware that all C# keywords are lowercase (e.g., public, lock, class, dynamic), while namespaces, types, and member names begin (by convetion) with an inital capital letter and the first letter of any embedded words is capitlized (e.g. , Console.WriteLine, System.Windows.MessageBox, System.Data.SqlClient). As a rule of thumb, whenever you receive a compiler error regarding "undifined sysmbols," be sure to check your spelling and casing first!
*/
```