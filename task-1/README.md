
В первой части курса мы будем погружаться в C#, научимся создавать переменные, вводить и выводить данные с клавиатуры.

Начнём с очень простых вещей, чтобы выровнять начальный уровень группы и дать возможность ознакомиться с инструментами разработки и коллаборации.

### Цели первого задания

* Установить [Visual Studio 2013 express](http://www.microsoft.com/en-us/download/details.aspx?id=43729),
* научиться рабоать с debug режимом vs,
* сделать простую задачку на C#
* познакомиться с Git и [GitHub](http://github.com/).

### Задание

1. Скачай и установи себе на компьютер [Visual Studio 2013 express](http://www.microsoft.com/en-us/download/details.aspx?id=43729). Если у тебя стоит старая версия 2012 или 2010, то можешь оставить её. Но лучше всётаки поставить новую версию, тем более она бесплатная

2. Запусти VS и создай новый Concole Application 
![Создание проекта][createproject]

3. У тебя создастся проект и автоматический откроется файл `Program.cs`. Этот файл будет содержать примерное такой код:
```
    using System;
    using System.Collections.Generic;
    using System.Linq;
    using System.Text;
    using System.Threading.Tasks;
    
    namespace Lesson1
    {
        class Program
        {
            static void Main(string[] args)
            {
            }
        }
    }
```
Мы будем с тобой писать программу внутри функции `static void Main(string[] args)`.

4. Внутри данной функции напиши следущий код и запусти программу.
```
    Console.Write("Введите первое число: ");
    string strA = Console.ReadLine();
    int a = int.Parse(strA);

    Console.Write("Введите второе число: "); 
    string strB = Console.ReadLine();
    int b = int.Parse(strB);

    int sum = a + b;
    Console.Write("{0} + {1} = {2}", a, b, sum);
    Console.ReadKey(); 
```

5. Измени программу так, чтобы вместо суммы, у тебя считалась разность 2-х чисел

6. Измени программу так, чтобы у тебя одновременно считались
  * Сумма
  * Разность
  * Произведение
  * Часное

7. Выложи своё решение на **Github** 

[createproject]: https://raw.githubusercontent.com/maxigrom/csharp_course/master/task-1/new_project.png

### Ссылки для справки и самостоятельного изучения:

C#:
* Арифметические операции в C# http://www.tutorialspoint.com/csharp/csharp_operators.htm

Git:
* http://habrahabr.ru/post/125799/
* http://git-scm.com/book/ru
