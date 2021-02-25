# Arrays  
just arrays  
  
thx to the tutorials: https://www.youtube.com/channel/UCVdfgrCLfJQfO5EgPlzaYAQ  [German]

```c#
using System;

namespace Arrays
{
    class Program
    {
        static void Main(string[] args)
        {
            {
                string[] namensListe = new string[3];
                namensListe[0] = "Melvin";
                namensListe[1] = "James";
                namensListe[2] = "Edward";

                Console.WriteLine(namensListe[2]);
            }
            {
                int[] integerListe = new int[4];

                integerListe[0] = 10;
                integerListe[1] = 20;
                integerListe[1] = 30;
                integerListe[3] = 40;

                Console.WriteLine(integerListe[3]);
            }
            Console.ReadKey();
        }
    }
}
```
