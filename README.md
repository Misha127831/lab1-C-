Вопросы 
8  Console.WriteLine("Введите числа");
            Console.WriteLine(double.Parse(Console.ReadLine()) + double.Parse(Console.ReadLine()));
            Console.ReadKey();
15  
        static void Main()
        {
            var res = SquareSum(1, 2);
            Console.WriteLine("Ответ: {0}", res); //Выведет 9.
            Console.ReadKey();
        }
 
        static double SquareSum(double x, double y)
        {
            double sum = x + y;
            double result = Math.Pow(sum, 2);
 
            return result;
        }
  22    static void Main(string[] args)
        {
 
            Console.WriteLine("Введите число №1");
            string s = Console.ReadLine();
            int v = Convert.ToInt32(s);
            Console.WriteLine("Введите число №2");
            string r = Console.ReadLine();
            int c = Convert.ToInt32(r);
            int частное = v / c;
            double d = Math.Pow(частное, 3);
            Console.WriteLine("Возведение в куб частного чиел 1 и 2 ={0}",d);
            
 
        }
  5   Да,CLR также используется в C#, Managed C++, Visual Basic .NET, F# и тд
  12public int GetDiffSquare(int arg1, int arg2)
{
    int diff = arg1 - arg2; 
    return diff * diff;    
}
...
int res = GetDiffSquare(2, 5); 
