using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp6
{
    internal class Program
    {
        static void Main(string[] args)
        {
            
            int age = 18;
            Console.WriteLine("Ваш возраст   = " + age);


            
            long bill;
            bill = 1000000000;
            Console.WriteLine("На данный момен ваш счет равен  " + bill);

           
            char simvol = '@';
            Console.WriteLine("Вы ввели  " + simvol);

            string SMS = "Hello world";
            Console.WriteLine("Вам пришло сообщение " + SMS);           
                
            bool pravda = false;
            Console.WriteLine("Ответ соседа оказался " + pravda);


            double degres = 36.6;
            Console.WriteLine("Температура человека составляет " + degres + " градусов");

            long peoples = 7500000000;
            Console.WriteLine("Планете живет более " + peoples + " человек");

            double climat = 9;
            Console.WriteLine("Температура окружающей среды составляет + " + climat + " градусов ");
             
        }
    }
}



using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int password = 1607;
            int npassword = 1023;
            int g;
            string b = "User";
            string a;
            string c = "Admin";      
            string e = "";

            Console.WriteLine("Введите логин");
            a = Console.ReadLine();
            if (a == b)
            {
                Console.WriteLine("Введите пароль");
                g = Convert.ToInt32(Console.ReadLine());

                if (g == password)
                {
                    Console.WriteLine("Hello User");
                }
                else
                {
                    Console.WriteLine("Password is not correct");
                }

            }
            if (a == c)
            {
                Console.WriteLine("Введите пароль");
                g = Convert.ToInt32(Console.ReadLine());
                if (g == npassword)
                {
                    Console.WriteLine("Hello administrator");
                }

            }
            if (a == e)
            {
                Console.WriteLine("Hello Anonimous");
            }


        }
    }
}

