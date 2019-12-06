class Program
    {
        static void SwapIt(ref int x, ref int y)
        {
            int temp = x;
            x = y;
            y = temp;
        }
        static void Main()
        {
            int i = 2, j = 3;
            Console.WriteLine("i={0} j+{1}", i, j);

            SwapIt(ref i, ref j);

            Console.WriteLine("i={0} j+{1}", i, j);

            Console.WriteLine("press any key to exit");
            Console.ReadKey();
        }
