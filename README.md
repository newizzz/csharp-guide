# CSharp
Перед тем, как мы начнем, нужно убедиться, что у вас установлены необходимые программы. Для языка программирования C# вам понадобится Visual Studio. Вы можете загрузить его с официального сайта Microsoft.

Теперь, когда вы установили Visual Studio, мы можем начать.

Hello World!
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

csharp
Copy code
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
