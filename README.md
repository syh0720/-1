C#学习代码
using System;

namespace lianxihour
{
    class Program
    {
        static void Main(string[] args)
        {
            var input = Convert.ToInt32(Console.ReadLine());
            var hour = input / 3600;
            var min = input % 3600 / 60;
            var s = input % 60;

            if (hour > 0)
            {
                Console.Write("{0}小时", hour);
            }
            if (min > 0)
            {
                Console.Write("{0}分钟", min);
            }
            Console.Write("{0}秒", s);
        }
    }
}
