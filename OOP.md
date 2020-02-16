# Maria_Manastirli_task_MM
using System;

namespace taks_Maria_Manastirli
{
    public class Write
    {
       

        public void PrintInfo (int num)
        {
            string line = "-";
            string star = "*";


            if (num % 2 != 0)
            {

                for (int i = 0; i < num + 1; i++)//repead rows
                {

                    for (int m = 0; m < 2; m++)//kopira 1/2 rows v drugata polvina na reda
                    {
                        for (int u = 0; u < 2; u++)//izpisva 2 pyti po num broi "*" i "-'
                        {

                            for (int l = 0; l < num; l++)//printira liniite
                            {

                                Console.Write(line);
                            }

                            for (int s = 0; s < num; s++)//printira zwezdite
                            {
                                Console.Write(star);
                            }
                        }
                        for (int l = 0; l < num; l++)//printira oshte edin red linii                     {
                        {
                            Console.Write(line);
                        }
                    }
                    Console.WriteLine();
                }
            }

            else
                Console.WriteLine("Invailed number");


            Console.ReadKey();

        }

    }
}
sing System;

namespace taks_Maria_Manastirli
{
    public class Program
    {
        public static void Main(string[] args)
        {
            ///С ООП успях да стигна само до тук :(
            ///

            Write number = new Write();
            number.PrintInfo(5);
                                   
            Console.ReadKey();
        }
        
    }
    

}
