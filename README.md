# Neriman-Alt-nokusing System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication67
{
    class Program
    {
        static void Main(string[] args)
        {
            char i; int a = 10, t, u; string c, kelime = "";
            Console.WriteLine("isminizi giriniz="); c = Console.ReadLine();
            u = c.Length;
            for (int p = 0; p < u; p++)
            {
                Console.Write("isminizin {0}. harfinizi giriniz=", p + 1); i = char.Parse(Console.ReadLine());
                t = a + (int)i;
                kelime += (char)t;
            }
            Console.Write("ASCII kodunun 10 fazlası :" + kelime);
            Console.ReadLine();
        }
    }
}
