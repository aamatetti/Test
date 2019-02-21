using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.IO;

namespace DocuemntApp
{
    class Program
    {
        static void Main(string[] args)
        {
            try
            {
                Console.WriteLine("Docuemnt");
                Console.WriteLine();
                Console.WriteLine("Enter doc name");
                string name = Console.ReadLine();
                Console.WriteLine("Enter doc contents");
                string content = Console.ReadLine();
                string filename = name + ".txt";
                string path = Environment.CurrentDirectory + "/" + filename;
                if (!File.Exists(path))
                {
                    File.WriteAllText(path, content);
                }
                Console.WriteLine(filename + " was successfully saved. The document contains " + content.Length + " characters");

            }

            catch (Exception e)

            {

                Console.WriteLine(e);
            }
            Console.ReadLine();
        }
    }
}
