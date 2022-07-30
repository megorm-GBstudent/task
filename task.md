**The solution of the task**

Console.WriteLine("Введите любой текст: ");
string text = Console.ReadLine();


Zadacha1(text);
void Zadacha1(string currentText)

{
    Console.WriteLine("_________________");
    Console.WriteLine("Решение");

    if (currentText.Length <= 3)
    {
        Console.WriteLine($"{currentText}");
    }
    else
    {
        Console.WriteLine("");
    }
}

