# CSharp
Перед тем, как мы начнем, нужно убедиться, что у вас установлены необходимые программы. Для языка программирования C# вам понадобится Visual Studio. Вы можете загрузить его с официального сайта Microsoft.

Теперь, когда вы установили Visual Studio, мы можем начать.

## Hello World!
Давайте начнем с программы "Hello World!", которая выводит простое сообщение на экран:

```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Hello, World!");
    }
}
```
## Переменные
Переменные - это места в памяти, где мы можем хранить значения. В языке C# есть несколько типов данных, которые вы можете использовать для определения переменных:

```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        int myInt = 42;
        double myDouble = 3.14;
        bool myBool = true;
        string myString = "Hello, World!";

        Console.WriteLine(myInt);
        Console.WriteLine(myDouble);
        Console.WriteLine(myBool);
        Console.WriteLine(myString);
    }
}
```
## Операторы
Операторы - это символы, которые мы используем для выполнения операций над значениями. Вот некоторые операторы, которые вы можете использовать в C#:

```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        int x = 10;
        int y = 5;

        int sum = x + y;
        int difference = x - y;
        int product = x * y;
        int quotient = x / y;
        int remainder = x % y;

        Console.WriteLine(sum);
        Console.WriteLine(difference);
        Console.WriteLine(product);
        Console.WriteLine(quotient);
        Console.WriteLine(remainder);
    }
}
```
## Условные операторы
Условные операторы позволяют выполнять определенный блок кода в зависимости от условия. Вот пример программы, которая выводит сообщение, если значение переменной больше 10:

```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        int x = 15;

        if (x > 10)
        {
            Console.WriteLine("x is greater than 10");
        }
    }
}
```
## Циклы
Циклы - это конструкции, которые позволяют нам выполнять блок кода несколько раз. Вот пример программы, которая выводит числа от 1 до 10:

```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        for (int i = 1; i <= 10; i++)
        {
            Console.WriteLine(i);
        }
    }
}
```

## Массивы
Массивы - это структуры данных, которые позволяют нам хранить несколько значений в одной переменной. Вот пример программы, которая создает массив чисел и выводит их на
экран:
```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        int[] myArray = { 1, 2, 3, 4, 5 };

        for (int i = 0; i < myArray.Length; i++)
        {
            Console.WriteLine(myArray[i]);
        }
    }
}
```

## Функции
Функции - это блоки кода, которые мы можем вызывать из других частей программы. Вот пример программы, которая определяет функцию для вычисления суммы двух чисел:

```csharp

using System;

class Program
{
    static void Main(string[] args)
    {
        int x = 5;
        int y = 10;

        int sum = AddNumbers(x, y);

        Console.WriteLine(sum);
    }

    static int AddNumbers(int a, int b)
    {
        return a + b;
    }
}
```
## Классы
Классы - это шаблоны, которые мы используем для создания объектов. Они содержат данные и функции для работы с этими данными. Вот пример программы, которая определяет класс для хранения информации о студентах:

```csharp
using System;

class Student
{
    public string Name { get; set; }
    public int Age { get; set; }
    public string Major { get; set; }

    public void PrintInfo()
    {
        Console.WriteLine("Name: " + Name);
        Console.WriteLine("Age: " + Age);
        Console.WriteLine("Major: " + Major);
    }
}

class Program
{
    static void Main(string[] args)
    {
        Student john = new Student();
        john.Name = "John Smith";
        john.Age = 20;
        john.Major = "Computer Science";

        john.PrintInfo();
    }
}
```
*Это был быстрый обзор основных конструкций языка программирования C#. Надеюсь, это поможет вам начать программировать!*
