
        Console.Write("ведіть перше число яке буде значеням: ");
        double value = Convert.ToDouble(Console.ReadLine());
        Console.Write("ведіть друге число яке буде процентом: ");
        double percent = Convert.ToDouble(Console.ReadLine());
        double result = value * percent / 100;
        Console.WriteLine($"{percent}% від {value} дорівнює {result}");
