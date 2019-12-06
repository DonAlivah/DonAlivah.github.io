using (StreamWriter sw = new StreamWriter("timesTables.txt"))
            {
                Console.WriteLine("enter a number");
                int number = Convert.ToUInt16(Console.ReadLine());
                for (int i = 0; i < number + 1; i++)

                {
                    int ttables = number * i;
                    //Console.WriteLine(ttables);
                    sw.WriteLine(Console.ReadLine());
                }
            }
            using (StreamReader sr = new StreamReader("timesTables.txt")) 
            {
                string timestables = sr.ReadLine();
                Console.WriteLine(timestables);
                Console.ReadLine();
            }
