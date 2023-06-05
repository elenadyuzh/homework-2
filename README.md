# homework-2

//Задача 1

 Console.WriteLine("Введите трехзначное число");
 int num = Convert.ToInt32(Console.ReadLine);
 int a = (num/10)%10;
 Console.WriteLine($"Второе число равно {a}");

 //Задача 2

 Console.WriteLine("Введите число");
 int num = Convert.ToInt32(Console.ReadLine);
 int b = (num/100)%10;
 if (b != 0)
 {
    Console.WriteLine($"Третья цифра числа равна {a}");
 }
 else
 {
  Console.WriteLine($"третьей цифры числа {num} не существует");  
 }
 


 