using System;

namespace Methods
{
    class Program
    {
        static void Main(string[] args)
        {

            Console.WriteLine("Sozunuzu daxil edin");
            string temp_word = Console.ReadLine();    


            Console.WriteLine("Herf Daxil Edin");
            char c;
            char.TryParse(Console.ReadLine(), out c);


            Console.WriteLine(FindCharIndex(temp_word, c));

        }
        static int FindCharIndex(string temp_word, char c)
        {
            char[] charString = temp_word.ToCharArray();
            for (int i = 0; i < temp_word.Length; i++)
            {

                if (c == charString[i])
                {

                    return i;
                }

            }
            return -1;
        }
    }
}
