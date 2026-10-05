# Готовые решения задач по практической работе №3




--

## Исходный код проекта

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.Write("Введите номер задачи (1-200): ");
        if (!int.TryParse(Console.ReadLine(), out int number))
        {
            Console.WriteLine("Некорректный ввод!");
            return;
        }
        Console.WriteLine();

        switch (number)
        {
            case 1: Task1(); break;
            case 2: Task2(); break;
            case 3: Task3(); break;
            case 4: Task4(); break;
            case 5: Task5(); break;
            case 6: Task6(); break;
            case 7: Task7(); break;
            case 8: Task8(); break;
            case 9: Task9(); break;
            case 10: Task10(); break;
            case 11: Task11(); break;
            case 12: Task12(); break;
            case 13: Task13(); break;
            case 14: Task14(); break;
            case 15: Task15(); break;
            case 16: Task16(); break;
            case 17: Task17(); break;
            case 18: Task18(); break;
            case 19: Task19(); break;
            case 20: Task20(); break;
            case 21: Task21(); break;
            case 22: Task22(); break;
            case 23: Task23(); break;
            case 24: Task24(); break;
            case 25: Task25(); break;
            case 26: Task26(); break;
            case 27: Task27(); break;
            case 28: Task28(); break;
            case 29: Task29(); break;
            case 30: Task30(); break;
            case 31: Task31(); break;
            case 32: Task32(); break;
            case 33: Task33(); break;
            case 34: Task34(); break;
            case 35: Task35(); break;
            case 36: Task36(); break;
            case 37: Task37(); break;
            case 38: Task38(); break;
            case 39: Task39(); break;
            case 40: Task40(); break;
            case 41: Task41(); break;
            case 42: Task42(); break;
            case 43: Task43(); break;
            case 44: Task44(); break;
            case 45: Task45(); break;
            case 46: Task46(); break;
            case 47: Task47(); break;
            case 48: Task48(); break;
            case 49: Task49(); break;
            case 50: Task50(); break;
            case 51: Task51(); break;
            case 52: Task52(); break;
            case 53: Task53(); break;
            case 54: Task54(); break;
            case 55: Task55(); break;
            case 56: Task56(); break;
            case 57: Task57(); break;
            case 58: Task58(); break;
            case 59: Task59(); break;
            case 60: Task60(); break;
            case 61: Task61(); break;
            case 62: Task62(); break;
            case 63: Task63(); break;
            case 64: Task64(); break;
            case 65: Task65(); break;
            case 66: Task66(); break;
            case 67: Task67(); break;
            case 68: Task68(); break;
            case 69: Task69(); break;
            case 70: Task70(); break;
            case 71: Task71(); break;
            case 72: Task72(); break;
            case 73: Task73(); break;
            case 74: Task74(); break;
            case 75: Task75(); break;
            case 76: Task76(); break;
            case 77: Task77(); break;
            case 78: Task78(); break;
            case 79: Task79(); break;
            case 80: Task80(); break;
            case 81: Task81(); break;
            case 82: Task82(); break;
            case 83: Task83(); break;
            case 84: Task84(); break;
            case 85: Task85(); break;
            case 86: Task86(); break;
            case 87: Task87(); break;
            case 88: Task88(); break;
            case 89: Task89(); break;
            case 90: Task90(); break;
            case 91: Task91(); break;
            case 92: Task92(); break;
            case 93: Task93(); break;
            case 94: Task94(); break;
            case 95: Task95(); break;
            case 96: Task96(); break;
            case 97: Task97(); break;
            case 98: Task98(); break;
            case 99: Task99(); break;
            case 100: Task100(); break;
            case 101: Task101(); break;
            case 102: Task102(); break;
            case 103: Task103(); break;
            case 104: Task104(); break;
            case 105: Task105(); break;
            case 106: Task106(); break;
            case 107: Task107(); break;
            case 108: Task108(); break;
            case 109: Task109(); break;
            case 110: Task110(); break;
            case 111: Task111(); break;
            case 112: Task112(); break;
            case 113: Task113(); break;
            case 114: Task114(); break;
            case 115: Task115(); break;
            case 116: Task116(); break;
            case 117: Task117(); break;
            case 118: Task118(); break;
            case 119: Task119(); break;
            case 120: Task120(); break;
            case 121: Task121(); break;
            case 122: Task122(); break;
            case 123: Task123(); break;
            case 124: Task124(); break;
            case 125: Task125(); break;
            case 126: Task126(); break;
            case 127: Task127(); break;
            case 128: Task128(); break;
            case 129: Task129(); break;
            case 130: Task130(); break;
            case 131: Task131(); break;
            case 132: Task132(); break;
            case 133: Task133(); break;
            case 134: Task134(); break;
            case 135: Task135(); break;
            case 136: Task136(); break;
            case 137: Task137(); break;
            case 138: Task138(); break;
            case 139: Task139(); break;
            case 140: Task140(); break;
            case 141: Task141(); break;
            case 142: Task142(); break;
            case 143: Task143(); break;
            case 144: Task144(); break;
            case 145: Task145(); break;
            case 146: Task146(); break;
            case 147: Task147(); break;
            case 148: Task148(); break;
            case 149: Task149(); break;
            case 150: Task150(); break;
            case 151: Task151(); break;
            case 152: Task152(); break;
            case 153: Task153(); break;
            case 154: Task154(); break;
            case 155: Task155(); break;
            case 156: Task156(); break;
            case 157: Task157(); break;
            case 158: Task158(); break;
            case 159: Task159(); break;
            case 160: Task160(); break;
            case 161: Task161(); break;
            case 162: Task162(); break;
            case 163: Task163(); break;
            case 164: Task164(); break;
            case 165: Task165(); break;
            case 166: Task166(); break;
            case 167: Task167(); break;
            case 168: Task168(); break;
            case 169: Task169(); break;
            case 170: Task170(); break;
            case 171: Task171(); break;
            case 172: Task172(); break;
            case 173: Task173(); break;
            case 174: Task174(); break;
            case 175: Task175(); break;
            case 176: Task176(); break;
            case 177: Task177(); break;
            case 178: Task178(); break;
            case 179: Task179(); break;
            case 180: Task180(); break;
            case 181: Task181(); break;
            case 182: Task182(); break;
            case 183: Task183(); break;
            case 184: Task184(); break;
            case 185: Task185(); break;
            case 186: Task186(); break;
            case 187: Task187(); break;
            case 188: Task188(); break;
            case 189: Task189(); break;
            case 190: Task190(); break;
            case 191: Task191(); break;
            case 192: Task192(); break;
            case 193: Task193(); break;
            case 194: Task194(); break;
            case 195: Task195(); break;
            case 196: Task196(); break;
            case 197: Task197(); break;
            case 198: Task198(); break;
            case 199: Task199(); break;
            case 200: Task200(); break;
            default: Console.WriteLine("Такой задачи нет"); break;
        }
    }


    // 1
    static void Task1()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num > 0)
        {
            Console.WriteLine("Число положительное");
        }
        else
        {
            Console.WriteLine("Число не является положительным");
        }
    }

    // 2
    static void Task2()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 2 == 0)
        {
            Console.WriteLine("Число четное");
        }
        else
        {
            Console.WriteLine("Число нечетное");
        }
    }

    // 3
    static void Task3()
    {
        Console.Write("Введите первое целое число: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите второе целое число: ");
        int b = int.Parse(Console.ReadLine());

        if (a > b)
        {
            Console.WriteLine("Наибольшее число: " + a);
        }
        else
        {
            Console.WriteLine("Наибольшее число: " + b);
        }
    }

    // 4
    static void Task4()
    {
        Console.Write("Введите первое число: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите второе число: ");
        double b = double.Parse(Console.ReadLine());

        if (a < b)
        {
            Console.WriteLine("Наименьшее число: " + a);
        }
        else
        {
            Console.WriteLine("Наименьшее число: " + b);
        }
    }

    // 5
    static void Task5()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 5 == 0)
        {
            Console.WriteLine("Делится на 5 нацело");
        }
        else
        {
            Console.WriteLine("Не делится на 5 нацело");
        }
    }

    // 6
    static void Task6()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 10 == 0)
        {
            Console.WriteLine("Число оканчивается нулем");
        }
        else
        {
            Console.WriteLine("Число не оканчивается нулем");
        }
    }

    // 7
    static void Task7()
    {
        Console.Write("Введите температуру воздуха: ");
        double temp = double.Parse(Console.ReadLine());

        if (temp < 0)
        {
            Console.WriteLine("На улице мороз, наденьте шапку");
        }
    }

    // 8
    static void Task8()
    {
        Console.Write("Введите число: ");
        double num = double.Parse(Console.ReadLine());

        if (num > 100)
        {
            num = num - 20;
        }
        else
        {
            num = num + 10;
        }

        Console.WriteLine("Результат: " + num);
    }

    // 9
    static void Task9()
    {
        Console.Write("Введите первое число: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите второе число: ");
        double b = double.Parse(Console.ReadLine());

        if (a == b)
        {
            Console.WriteLine("Числа равны");
        }
        else
        {
            Console.WriteLine("Произведение: " + (a * b));
        }
    }

    // 10
    static void Task10()
    {
        Console.Write("Введите возраст: ");
        int age = int.Parse(Console.ReadLine());

        if (age >= 18)
        {
            Console.WriteLine("Доступ разрешен");
        }
        else
        {
            Console.WriteLine("Доступ запрещен");
        }
    }

    // 11
    static void Task11()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());
        int absNum = Math.Abs(num);

        if (absNum >= 100 && absNum <= 999)
        {
            Console.WriteLine("Да");
        }
        else
        {
            Console.WriteLine("Нет");
        }
    }

    // 12
    static void Task12()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 3 == 0)
        {
            Console.WriteLine("Делится на 3 без остатка");
        }
        else
        {
            Console.WriteLine("Не делится на 3 без остатка");
        }
    }

    // 13
    static void Task13()
    {
        Console.Write("Введите координату X: ");
        double x = double.Parse(Console.ReadLine());

        if (x > 0)
        {
            Console.WriteLine("Точка лежит правее нуля");
        }
        else
        {
            Console.WriteLine("Точка не лежит правее нуля");
        }
    }

    // 14
    static void Task14()
    {
        Console.Write("Введите баланс счета: ");
        double balance = double.Parse(Console.ReadLine());

        if (balance < 0)
        {
            Console.WriteLine("Задолженность!");
        }
    }

    // 15
    static void Task15()
    {
        Console.Write("Введите пароль: ");
        int password = int.Parse(Console.ReadLine());

        if (password == 1234)
        {
            Console.WriteLine("Вход выполнен");
        }
        else
        {
            Console.WriteLine("Неверный пароль");
        }
    }

    // 16
    static void Task16()
    {
        Console.Write("Введите число: ");
        double num = double.Parse(Console.ReadLine());

        if (num < 0)
        {
            Console.WriteLine("Число отрицательное");
        }
        else
        {
            Console.WriteLine("Число неотрицательное");
        }
    }

    // 17
    static void Task17()
    {
        Console.Write("Введите первое число: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите второе число: ");
        double b = double.Parse(Console.ReadLine());

        if (a > b)
        {
            Console.WriteLine("Разность: " + (a - b));
        }
        else
        {
            Console.WriteLine("Разность: " + (b - a));
        }
    }

    // 18
    static void Task18()
    {
        Console.Write("Введите сумму покупки: ");
        double sum = double.Parse(Console.ReadLine());

        if (sum > 1000)
        {
            sum = sum * 0.95;
        }

        Console.WriteLine("Итоговая цена: " + sum);
    }

    // 19
    static void Task19()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 2 == 0)
        {
            Console.WriteLine("Результат: " + (num / 2));
        }
        else
        {
            Console.WriteLine("Результат: " + (num * 3));
        }
    }

    // 20
    static void Task20()
    {
        Console.Write("Введите скорость движения (км/ч): ");
        double speed = double.Parse(Console.ReadLine());

        if (speed > 90)
        {
            Console.WriteLine("Превышение скорости! Нарушение!");
        }
    }

    // 21
    static void Task21()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num == 0)
        {
            Console.WriteLine("Число равно нулю");
        }
        else
        {
            Console.WriteLine("Число не равно нулю");
        }
    }

    // 22
    static void Task22()
    {
        Console.Write("Введите первое число: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите второе число: ");
        double b = double.Parse(Console.ReadLine());

        if (Math.Abs(a - b) < 0.001)
        {
            Console.WriteLine("Числа равны с точностью до 0.001");
        }
        else
        {
            Console.WriteLine("Числа не равны с точностью до 0.001");
        }
    }

    // 23
    static void Task23()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());

        if (b != 0 && a % b == 0)
        {
            Console.WriteLine("A делится на B без остатка");
        }
        else
        {
            Console.WriteLine("A не делится на B без остатка");
        }
    }

    // 24
    static void Task24()
    {
        Console.Write("Введите первый угол: ");
        double angle1 = double.Parse(Console.ReadLine());
        Console.Write("Введите второй угол: ");
        double angle2 = double.Parse(Console.ReadLine());

        if (angle1 + angle2 < 180 && angle1 > 0 && angle2 > 0)
        {
            Console.WriteLine("Треугольник существует");
        }
        else
        {
            Console.WriteLine("Треугольник не существует");
        }
    }

    // 25
    static void Task25()
    {
        Console.Write("Введите радиус круга: ");
        double r = double.Parse(Console.ReadLine());
        Console.Write("Введите сторону квадрата: ");
        double a = double.Parse(Console.ReadLine());

        double circleArea = Math.PI * r * r;
        double squareArea = a * a;

        if (circleArea > squareArea)
        {
            Console.WriteLine("Площадь круга больше");
        }
        else if (squareArea > circleArea)
        {
            Console.WriteLine("Площадь квадрата больше");
        }
        else
        {
            Console.WriteLine("Площади равны");
        }
    }

    // 26
    static void Task26()
    {
        Console.Write("Введите первое число: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите второе число: ");
        double b = double.Parse(Console.ReadLine());

        double max = a > b ? a : b;
        double min = a < b ? a : b;

        if (min == 0)
        {
            Console.WriteLine("Ошибка: деление на ноль!");
        }
        else
        {
            Console.WriteLine("Частное большего на меньшее: " + (max / min));
        }
    }

    // 27
    static void Task27()
    {
        Console.Write("Введите целое число: ");
        int num = Math.Abs(int.Parse(Console.ReadLine()));

        if (num % 10 == 7)
        {
            Console.WriteLine("Последняя цифра - семь");
        }
        else
        {
            Console.WriteLine("Последняя цифра - не семь");
        }
    }

    // 28
    static void Task28()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num > 0 && num % 2 != 0)
        {
            Console.WriteLine("Да");
        }
        else
        {
            Console.WriteLine("Нет");
        }
    }

    // 29
    static void Task29()
    {
        Console.Write("Введите объем свободного места (ГБ): ");
        double space = double.Parse(Console.ReadLine());

        if (space < 5)
        {
            Console.WriteLine("Предупреждение: мало свободного места!");
        }
    }

    // 30
    static void Task30()
    {
        Console.Write("Введите оценку (2-5): ");
        int mark = int.Parse(Console.ReadLine());

        if (mark == 4 || mark == 5)
        {
            Console.WriteLine("Молодец");
        }
        else
        {
            Console.WriteLine("Нужно подтянуться");
        }
    }

    // 31
    static void Task31()
    {
        Console.Write("Введите первый символ: ");
        char c1 = char.Parse(Console.ReadLine());
        Console.Write("Введите второй символ: ");
        char c2 = char.Parse(Console.ReadLine());

        if (c1 == c2)
        {
            Console.WriteLine("Символы совпадают");
        }
        else
        {
            Console.WriteLine("Символы не совпадают");
        }
    }

    // 32
    static void Task32()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 2 == 0 && num % 7 == 0)
        {
            Console.WriteLine("Кратно 14");
        }
        else
        {
            Console.WriteLine("Не кратно 14");
        }
    }

    // 33
    static void Task33()
    {
        Console.Write("Введите массу груза (в тоннах): ");
        double mass = double.Parse(Console.ReadLine());

        if (mass > 3.5)
        {
            Console.WriteLine("Перегруз!");
        }
    }

    // 34
    static void Task34()
    {
        Console.Write("Введите текущий час (0-23): ");
        int hour = int.Parse(Console.ReadLine());

        if (hour >= 6 && hour <= 12)
        {
            Console.WriteLine("Доброе утро");
        }
    }

    // 35
    static void Task35()
    {
        Console.Write("Введите рост (см): ");
        double height = double.Parse(Console.ReadLine());

        if (height > 200)
        {
            Console.WriteLine("Очень высокий");
        }
    }

    // 36
    static void Task36()
    {
        Console.Write("Введите двузначное число: ");
        int num = Math.Abs(int.Parse(Console.ReadLine()));

        int first = num / 10;
        int second = num % 10;

        if (first > second)
        {
            Console.WriteLine("Первая цифра больше");
        }
        else if (second > first)
        {
            Console.WriteLine("Вторая цифра больше");
        }
        else
        {
            Console.WriteLine("Цифры равны");
        }
    }

    // 37
    static void Task37()
    {
        Console.Write("Введите стоимость товара: ");
        double price = double.Parse(Console.ReadLine());

        if (price == 0)
        {
            Console.WriteLine("Акция!");
        }
    }

    // 38
    static void Task38()
    {
        Console.Write("Введите двузначное число: ");
        int num = Math.Abs(int.Parse(Console.ReadLine()));

        int first = num / 10;
        int second = num % 10;

        if (first == second)
        {
            Console.WriteLine("Цифры одинаковые");
        }
        else
        {
            Console.WriteLine("Цифры разные");
        }
    }

    // 39
    static void Task39()
    {
        Console.Write("Введите уровень громкости (0-100): ");
        int vol = int.Parse(Console.ReadLine());

        if (vol > 80)
        {
            Console.WriteLine("Слишком громко для слуха");
        }
    }

    // 40
    static void Task40()
    {
        Console.Write("Введите первое число: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите второе число: ");
        int b = int.Parse(Console.ReadLine());

        if ((a + b) % 2 == 0)
        {
            Console.WriteLine("Сумма: " + (a + b));
        }
        else
        {
            Console.WriteLine("Разность: " + (a - b));
        }
    }

    // 41
    static void Task41()
    {
        Console.Write("Введите количество страниц: ");
        int pages = int.Parse(Console.ReadLine());

        if (pages > 100)
        {
            Console.WriteLine("Включить двухстороннюю печать");
        }
    }

    // 42
    static void Task42()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num >= 0)
        {
            double sqrt = Math.Sqrt(num);
            if (sqrt == (int)sqrt)
            {
                Console.WriteLine("Является полным квадратом");
            }
            else
            {
                Console.WriteLine("Не является полным квадратом");
            }
        }
        else
        {
            Console.WriteLine("Не является полным квадратом");
        }
    }

    // 43
    static void Task43()
    {
        Console.Write("Введите атмосферное давление (мм рт. ст.): ");
        double pressure = double.Parse(Console.ReadLine());

        if (pressure < 740)
        {
            Console.WriteLine("Пониженное давление");
        }
    }

    // 44
    static void Task44()
    {
        Console.Write("Забито мячей командой А: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Забито мячей командой Б: ");
        int b = int.Parse(Console.ReadLine());

        if (a > b)
        {
            Console.WriteLine("Победила команда А");
        }
        else if (b > a)
        {
            Console.WriteLine("Победила команда Б");
        }
        else
        {
            Console.WriteLine("Ничья");
        }
    }

    // 45
    static void Task45()
    {
        Console.Write("Введите число: ");
        double num = double.Parse(Console.ReadLine());

        if (num < 0)
        {
            num = -num;
        }

        Console.WriteLine("Модуль числа: " + num);
    }

    // 46
    static void Task46()
    {
        Console.Write("Введите уровень сахара в крови (ммоль/л): ");
        double sugar = double.Parse(Console.ReadLine());

        if (sugar > 6.1)
        {
            Console.WriteLine("Выше нормы");
        }
    }

    // 47
    static void Task47()
    {
        Console.Write("Введите баланс счета: ");
        double balance = double.Parse(Console.ReadLine());

        if (balance >= 35)
        {
            Console.WriteLine("Средств достаточно для оплаты проезда");
        }
        else
        {
            Console.WriteLine("Недостаточно средств");
        }
    }

    // 48
    static void Task48()
    {
        Console.Write("Введите номер этажа: ");
        int floor = int.Parse(Console.ReadLine());

        if (floor > 10)
        {
            Console.WriteLine("Высотный этаж");
        }
    }

    // 49
    static void Task49()
    {
        Console.Write("Введите первое слово: ");
        string word1 = Console.ReadLine();
        Console.Write("Введите второе слово: ");
        string word2 = Console.ReadLine();

        if (word1.Length == word2.Length)
        {
            Console.WriteLine("Слова одинаковы по длине");
        }
        else
        {
            Console.WriteLine("Слова разной длины");
        }
    }

    // 50
    static void Task50()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 2 == 0)
        {
            Console.WriteLine("Число четное");
        }
        else
        {
            Console.WriteLine("Число нечетное");
        }
    }


    // 51
    static void Task51()
    {
        Console.Write("Введите балл за тест (0-100): ");
        int score = int.Parse(Console.ReadLine());

        if (score >= 90)
        {
            Console.WriteLine("A");
        }
        else if (score >= 80)
        {
            Console.WriteLine("B");
        }
        else if (score >= 70)
        {
            Console.WriteLine("C");
        }
        else if (score >= 60)
        {
            Console.WriteLine("D");
        }
        else
        {
            Console.WriteLine("F");
        }
    }

    // 52
    static void Task52()
    {
        Console.Write("Введите возраст: ");
        int age = int.Parse(Console.ReadLine());

        if (age <= 12)
        {
            Console.WriteLine("Ребенок");
        }
        else if (age <= 17)
        {
            Console.WriteLine("Подросток");
        }
        else if (age <= 64)
        {
            Console.WriteLine("Взрослый");
        }
        else
        {
            Console.WriteLine("Пожилой");
        }
    }

    // 53
    static void Task53()
    {
        Console.Write("Введите температуру воды (°C): ");
        double t = double.Parse(Console.ReadLine());

        if (t <= 0)
        {
            Console.WriteLine("Лед");
        }
        else if (t < 100)
        {
            Console.WriteLine("Жидкость");
        }
        else
        {
            Console.WriteLine("Пар");
        }
    }

    // 54
    static void Task54()
    {
        Console.Write("Введите заряд аккумулятора (%): ");
        int charge = int.Parse(Console.ReadLine());

        if (charge < 10)
        {
            Console.WriteLine("Критический");
        }
        else if (charge <= 20)
        {
            Console.WriteLine("Низкий");
        }
        else if (charge <= 80)
        {
            Console.WriteLine("Нормальный");
        }
        else
        {
            Console.WriteLine("Полный");
        }
    }

    // 55
    static void Task55()
    {
        Console.Write("Введите RPM двигателя: ");
        int rpm = int.Parse(Console.ReadLine());

        if (rpm == 0)
        {
            Console.WriteLine("Заглушен");
        }
        else if (rpm <= 900)
        {
            Console.WriteLine("Холостой ход");
        }
        else if (rpm <= 3500)
        {
            Console.WriteLine("Рабочий");
        }
        else
        {
            Console.WriteLine("Красная зона");
        }
    }

    // 56
    static void Task56()
    {
        Console.Write("Введите годовой доход (руб): ");
        double income = double.Parse(Console.ReadLine());

        if (income <= 2400000)
        {
            Console.WriteLine("Налог: " + (income * 0.13));
        }
        else if (income <= 5000000)
        {
            Console.WriteLine("Налог: " + (income * 0.15));
        }
        else
        {
            Console.WriteLine("Налог: " + (income * 0.18));
        }
    }

    // 57
    static void Task57()
    {
        Console.Write("Введите координату X: ");
        double x = double.Parse(Console.ReadLine());

        if (x == 0)
        {
            Console.WriteLine("На нуле");
        }
        else if (x > 0)
        {
            Console.WriteLine("В положительной полуоси");
        }
        else
        {
            Console.WriteLine("В отрицательной полуоси");
        }
    }

    // 58
    static void Task58()
    {
        Console.Write("Введите ИМТ: ");
        double bmi = double.Parse(Console.ReadLine());

        if (bmi < 18.5)
        {
            Console.WriteLine("Дефицит веса");
        }
        else if (bmi <= 24.9)
        {
            Console.WriteLine("Норма");
        }
        else if (bmi <= 29.9)
        {
            Console.WriteLine("Избыток веса");
        }
        else
        {
            Console.WriteLine("Ожирение");
        }
    }

    // 59
    static void Task59()
    {
        Console.Write("Введите скорость ветра (м/с): ");
        double v = double.Parse(Console.ReadLine());

        if (v < 0.2)
        {
            Console.WriteLine("Штиль");
        }
        else if (v <= 5)
        {
            Console.WriteLine("Легкий ветерок");
        }
        else if (v <= 14)
        {
            Console.WriteLine("Умеренный");
        }
        else if (v <= 24)
        {
            Console.WriteLine("Шторм");
        }
        else
        {
            Console.WriteLine("Ураган");
        }
    }

    // 60
    static void Task60()
    {
        Console.Write("Введите стаж работы (лет): ");
        double years = double.Parse(Console.ReadLine());

        if (years < 1)
        {
            Console.WriteLine("Надбавка: 0%");
        }
        else if (years <= 5)
        {
            Console.WriteLine("Надбавка: 5%");
        }
        else if (years <= 10)
        {
            Console.WriteLine("Надбавка: 10%");
        }
        else
        {
            Console.WriteLine("Надбавка: 15%");
        }
    }

    // 61
    static void Task61()
    {
        Console.Write("Введите час (0-23): ");
        int hour = int.Parse(Console.ReadLine());

        if (hour >= 0 && hour <= 5)
        {
            Console.WriteLine("Ночь");
        }
        else if (hour <= 11)
        {
            Console.WriteLine("Утро");
        }
        else if (hour <= 17)
        {
            Console.WriteLine("День");
        }
        else
        {
            Console.WriteLine("Вечер");
        }
    }

    // 62
    static void Task62()
    {
        Console.Write("Введите толщину льда (см): ");
        double ice = double.Parse(Console.ReadLine());

        if (ice < 7)
        {
            Console.WriteLine("Выход запрещен");
        }
        else if (ice <= 12)
        {
            Console.WriteLine("Одиночный пешеход");
        }
        else if (ice <= 20)
        {
            Console.WriteLine("Группа людей");
        }
        else
        {
            Console.WriteLine("Транспорт");
        }
    }

    // 63
    static void Task63()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());
        Console.Write("Введите число C: ");
        int c = int.Parse(Console.ReadLine());

        if (a >= b && a >= c)
        {
            Console.WriteLine("Максимум: " + a);
        }
        else if (b >= a && b >= c)
        {
            Console.WriteLine("Максимум: " + b);
        }
        else
        {
            Console.WriteLine("Максимум: " + c);
        }
    }

    // 64
    static void Task64()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());
        Console.Write("Введите число C: ");
        int c = int.Parse(Console.ReadLine());

        if (a <= b && a <= c)
        {
            Console.WriteLine("Минимум: " + a);
        }
        else if (b <= a && b <= c)
        {
            Console.WriteLine("Минимум: " + b);
        }
        else
        {
            Console.WriteLine("Минимум: " + c);
        }
    }

    // 65
    static void Task65()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());
        Console.Write("Введите число C: ");
        int c = int.Parse(Console.ReadLine());

        int count = 0;

        if (a > 0)
        {
            count++;
        }
        if (b > 0)
        {
            count++;
        }
        if (c > 0)
        {
            count++;
        }

        Console.WriteLine("Положительных чисел: " + count);
    }

    // 66
    static void Task66()
    {
        Console.Write("Введите средний балл: ");
        double gpa = double.Parse(Console.ReadLine());

        if (gpa < 4.5)
        {
            Console.WriteLine("Без отличия");
        }
        else if (gpa < 4.75)
        {
            Console.WriteLine("Претендент на красный диплом");
        }
        else
        {
            Console.WriteLine("Красный диплом");
        }
    }

    // 67
    static void Task67()
    {
        Console.Write("Введите систолическое давление: ");
        int p = int.Parse(Console.ReadLine());

        if (p < 90)
        {
            Console.WriteLine("Гипотония");
        }
        else if (p <= 120)
        {
            Console.WriteLine("Норма");
        }
        else if (p <= 139)
        {
            Console.WriteLine("Предгипертензия");
        }
        else
        {
            Console.WriteLine("Гипертензия");
        }
    }

    // 68
    static void Task68()
    {
        Console.Write("Введите рейтинг Эло: ");
        int elo = int.Parse(Console.ReadLine());

        if (elo < 1400)
        {
            Console.WriteLine("Любитель");
        }
        else if (elo <= 1999)
        {
            Console.WriteLine("Разрядник");
        }
        else if (elo <= 2399)
        {
            Console.WriteLine("Мастер");
        }
        else
        {
            Console.WriteLine("Гроссмейстер");
        }
    }

    // 69
    static void Task69()
    {
        Console.Write("Введите целое число: ");
        int num = Math.Abs(int.Parse(Console.ReadLine()));

        if (num < 10)
        {
            Console.WriteLine("Однозначное");
        }
        else if (num < 100)
        {
            Console.WriteLine("Двузначное");
        }
        else if (num < 1000)
        {
            Console.WriteLine("Трехзначное");
        }
        else
        {
            Console.WriteLine("Более трех знаков");
        }
    }

    // 70
    static void Task70()
    {
        Console.Write("Введите расстояние (км): ");
        double dist = double.Parse(Console.ReadLine());
        double cost;

        if (dist <= 5)
        {
            cost = 200;
        }
        else if (dist <= 15)
        {
            cost = 200 + (dist - 5) * 25;
        }
        else
        {
            cost = 200 + 10 * 25 + (dist - 15) * 20;
        }

        Console.WriteLine("Стоимость поездки: " + cost + " руб.");
    }

    // 71
    static void Task71()
    {
        Console.Write("Введите количество осадков (мм): ");
        double rain = double.Parse(Console.ReadLine());

        if (rain == 0)
        {
            Console.WriteLine("Без осадков");
        }
        else if (rain <= 4)
        {
            Console.WriteLine("Слабый дождь");
        }
        else if (rain <= 15)
        {
            Console.WriteLine("Умеренный дождь");
        }
        else
        {
            Console.WriteLine("Сильный ливень");
        }
    }

    // 72
    static void Task72()
    {
        Console.Write("Введите % выполнения плана: ");
        double plan = double.Parse(Console.ReadLine());

        if (plan < 70)
        {
            Console.WriteLine("План сорван");
        }
        else if (plan <= 99)
        {
            Console.WriteLine("Удовлетворительно");
        }
        else if (plan <= 119)
        {
            Console.WriteLine("Выполнен");
        }
        else
        {
            Console.WriteLine("Перевыполнен");
        }
    }

    // 73
    static void Task73()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());
        Console.Write("Введите число C: ");
        int c = int.Parse(Console.ReadLine());

        if (a > b)
        {
            int temp = a;
            a = b;
            b = temp;
        }
        if (b > c)
        {
            int temp = b;
            b = c;
            c = temp;
        }
        if (a > b)
        {
            int temp = a;
            a = b;
            b = temp;
        }

        Console.WriteLine("По возрастанию: " + a + ", " + b + ", " + c);
    }

    // 74
    static void Task74()
    {
        Console.Write("Введите X: ");
        double x = double.Parse(Console.ReadLine());
        double res;

        if (x > 0)
        {
            res = x * x;
        }
        else if (x == 0)
        {
            res = 0;
        }
        else
        {
            res = -x;
        }

        Console.WriteLine("f(x) = " + res);
    }

    // 75
    static void Task75()
    {
        Console.Write("Введите октановое число: ");
        int oct = int.Parse(Console.ReadLine());

        if (oct < 92)
        {
            Console.WriteLine("Несоответствие стандарту");
        }
        else if (oct == 92)
        {
            Console.WriteLine("АИ-92");
        }
        else if (oct == 95)
        {
            Console.WriteLine("АИ-95");
        }
        else if (oct <= 100)
        {
            Console.WriteLine("АИ-98/100");
        }
        else
        {
            Console.WriteLine("Спорт/Авиатопливо");
        }
    }

    // 76
    static void Task76()
    {
        Console.Write("Введите сумму покупок (руб): ");
        double sum = double.Parse(Console.ReadLine());
        double cashback;

        if (sum <= 10000)
        {
            cashback = sum * 0.01;
        }
        else if (sum <= 50000)
        {
            cashback = sum * 0.03;
        }
        else
        {
            cashback = sum * 0.05;
        }

        Console.WriteLine("Кешбэк: " + cashback + " руб.");
    }

    // 77
    static void Task77()
    {
        Console.Write("Введите глубину погружения (м): ");
        double depth = double.Parse(Console.ReadLine());

        if (depth < 40)
        {
            Console.WriteLine("Рекреационная зона");
        }
        else if (depth <= 100)
        {
            Console.WriteLine("Техническая зона");
        }
        else
        {
            Console.WriteLine("Глубоководная зона");
        }
    }

    // 78
    static void Task78()
    {
        Console.Write("Введите штрафные баллы: ");
        int pts = int.Parse(Console.ReadLine());

        if (pts >= 1 && pts <= 5)
        {
            Console.WriteLine("Предупреждение");
        }
        else if (pts <= 10)
        {
            Console.WriteLine("Временное ограничение");
        }
        else if (pts > 10)
        {
            Console.WriteLine("Лишение прав");
        }
        else
        {
            Console.WriteLine("Нарушений нет");
        }
    }

    // 79
    static void Task79()
    {
        Console.Write("Введите уровень pH: ");
        double ph = double.Parse(Console.ReadLine());

        if (ph < 6.0)
        {
            Console.WriteLine("Кислая");
        }
        else if (ph <= 7.2)
        {
            Console.WriteLine("Нейтральная");
        }
        else
        {
            Console.WriteLine("Щелочная");
        }
    }

    // 80
    static void Task80()
    {
        Console.Write("Введите очки: ");
        int score = int.Parse(Console.ReadLine());

        if (score >= 5000)
        {
            Console.WriteLine("Золотая медаль");
        }
        else if (score >= 2500)
        {
            Console.WriteLine("Серебряная медаль");
        }
        else if (score >= 1000)
        {
            Console.WriteLine("Бронзовая медаль");
        }
        else
        {
            Console.WriteLine("Без медали");
        }
    }

    // 81
    static void Task81()
    {
        Console.Write("Введите крепость (°): ");
        double alc = double.Parse(Console.ReadLine());

        if (alc == 0)
        {
            Console.WriteLine("Безалкогольный");
        }
        else if (alc <= 8)
        {
            Console.WriteLine("Слабоалкогольный");
        }
        else if (alc <= 25)
        {
            Console.WriteLine("Среднеалкогольный");
        }
        else
        {
            Console.WriteLine("Крепкий");
        }
    }

    // 82
    static void Task82()
    {
        Console.Write("Введите уровень шума (дБ): ");
        double db = double.Parse(Console.ReadLine());

        if (db < 40)
        {
            Console.WriteLine("Тихо");
        }
        else if (db <= 60)
        {
            Console.WriteLine("Норма");
        }
        else if (db <= 80)
        {
            Console.WriteLine("Шумно");
        }
        else
        {
            Console.WriteLine("Вредно для здоровья");
        }
    }

    // 83
    static void Task83()
    {
        Console.Write("Введите вес посылки (кг): ");
        double w = double.Parse(Console.ReadLine());

        if (w < 2)
        {
            Console.WriteLine("Мелкий пакет");
        }
        else if (w <= 10)
        {
            Console.WriteLine("Стандартная");
        }
        else if (w <= 31.5)
        {
            Console.WriteLine("Тяжеловесная");
        }
        else
        {
            Console.WriteLine("Крупногабарит");
        }
    }

    // 84
    static void Task84()
    {
        Console.Write("Введите количество комнат: ");
        int rooms = int.Parse(Console.ReadLine());

        if (rooms == 1)
        {
            Console.WriteLine("Студия / 1-комнатная");
        }
        else if (rooms == 2)
        {
            Console.WriteLine("2-комнатная");
        }
        else if (rooms == 3)
        {
            Console.WriteLine("3-комнатная");
        }
        else
        {
            Console.WriteLine("Многокомнатная (4+)");
        }
    }

    // 85
    static void Task85()
    {
        Console.Write("Введите % заряда повербанка: ");
        int pct = int.Parse(Console.ReadLine());

        if (pct <= 25)
        {
            Console.WriteLine("1 светодиод");
        }
        else if (pct <= 50)
        {
            Console.WriteLine("2 светодиода");
        }
        else if (pct <= 75)
        {
            Console.WriteLine("3 светодиода");
        }
        else
        {
            Console.WriteLine("4 светодиода");
        }
    }

    // 86
    static void Task86()
    {
        Console.Write("Введите выслугу лет: ");
        int y = int.Parse(Console.ReadLine());

        if (y < 10)
        {
            Console.WriteLine("Надбавка: 0%");
        }
        else if (y < 15)
        {
            Console.WriteLine("Надбавка: 10%");
        }
        else if (y < 20)
        {
            Console.WriteLine("Надбавка: 20%");
        }
        else
        {
            Console.WriteLine("Надбавка: 30%");
        }
    }

    // 87
    static void Task87()
    {
        Console.Write("Введите пинг (мс): ");
        int ping = int.Parse(Console.ReadLine());

        if (ping < 20)
        {
            Console.WriteLine("Идеальный");
        }
        else if (ping <= 60)
        {
            Console.WriteLine("Хороший");
        }
        else if (ping <= 120)
        {
            Console.WriteLine("Посредственный");
        }
        else
        {
            Console.WriteLine("Плохой");
        }
    }

    // 88
    static void Task88()
    {
        Console.Write("Введите концентрацию CO2 (ppm): ");
        int co2 = int.Parse(Console.ReadLine());

        if (co2 < 800)
        {
            Console.WriteLine("Норма");
        }
        else if (co2 <= 1200)
        {
            Console.WriteLine("Душно");
        }
        else
        {
            Console.WriteLine("Проветрить немедленно!");
        }
    }

    // 89
    static void Task89()
    {
        Console.Write("Введите количество шагов: ");
        int steps = int.Parse(Console.ReadLine());

        if (steps < 5000)
        {
            Console.WriteLine("Гиподинамия");
        }
        else if (steps <= 9999)
        {
            Console.WriteLine("Норма");
        }
        else if (steps <= 14999)
        {
            Console.WriteLine("Активный день");
        }
        else
        {
            Console.WriteLine("Рекорд!");
        }
    }

    // 90
    static void Task90()
    {
        Console.Write("Введите диаметр диска (дюймы): ");
        int r = int.Parse(Console.ReadLine());

        if (r <= 14)
        {
            Console.WriteLine("Малолитражки");
        }
        else if (r <= 16)
        {
            Console.WriteLine("Компактные авто");
        }
        else if (r <= 19)
        {
            Console.WriteLine("Кроссоверы / Бизнес");
        }
        else
        {
            Console.WriteLine("Внедорожники / Спорт");
        }
    }

    // 91
    static void Task91()
    {
        Console.Write("Введите влажность воздуха (%): ");
        double h = double.Parse(Console.ReadLine());

        if (h < 30)
        {
            Console.WriteLine("Сухой воздух");
        }
        else if (h <= 60)
        {
            Console.WriteLine("Комфорт");
        }
        else
        {
            Console.WriteLine("Повышенная влажность");
        }
    }

    // 92
    static void Task92()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());
        Console.Write("Введите число C: ");
        int c = int.Parse(Console.ReadLine());

        if (a == b && b == c)
        {
            Console.WriteLine("Все три равны");
        }
        else if (a == b || b == c || a == c)
        {
            Console.WriteLine("Два равны");
        }
        else
        {
            Console.WriteLine("Все разные");
        }
    }

    // 93
    static void Task93()
    {
        Console.Write("Введите номер четверти (1-4): ");
        int q = int.Parse(Console.ReadLine());

        if (q == 1)
        {
            Console.WriteLine("X > 0, Y > 0");
        }
        else if (q == 2)
        {
            Console.WriteLine("X < 0, Y > 0");
        }
        else if (q == 3)
        {
            Console.WriteLine("X < 0, Y < 0");
        }
        else if (q == 4)
        {
            Console.WriteLine("X > 0, Y < 0");
        }
        else
        {
            Console.WriteLine("Неверный номер четверти");
        }
    }

    // 94
    static void Task94()
    {
        Console.Write("Введите температуру ЦП (°C): ");
        double temp = double.Parse(Console.ReadLine());

        if (temp < 45)
        {
            Console.WriteLine("Холодный");
        }
        else if (temp <= 75)
        {
            Console.WriteLine("Нормальная нагрузка");
        }
        else
        {
            Console.WriteLine("Троттлинг / Перегрев!");
        }
    }

    // 95
    static void Task95()
    {
        Console.Write("Введите остаток срока (дней): ");
        int days = int.Parse(Console.ReadLine());

        if (days <= 2)
        {
            Console.WriteLine("Срочно употребить");
        }
        else if (days <= 30)
        {
            Console.WriteLine("Нормально");
        }
        else
        {
            Console.WriteLine("Длительное хранение");
        }
    }

    // 96
    static void Task96()
    {
        Console.Write("Введите срок кредита (лет): ");
        double years = double.Parse(Console.ReadLine());

        if (years <= 1)
        {
            Console.WriteLine("Процентная ставка: 12%");
        }
        else if (years <= 3)
        {
            Console.WriteLine("Процентная ставка: 15%");
        }
        else
        {
            Console.WriteLine("Процентная ставка: 18%");
        }
    }

    // 97
    static void Task97()
    {
        Console.Write("Введите частоту обновления (Гц): ");
        int hz = int.Parse(Console.ReadLine());

        if (hz <= 75)
        {
            Console.WriteLine("Офис");
        }
        else if (hz <= 144)
        {
            Console.WriteLine("Базовый игровой");
        }
        else
        {
            Console.WriteLine("Киберспорт");
        }
    }

    // 98
    static void Task98()
    {
        Console.Write("Введите расход топлива (л/100км): ");
        double f = double.Parse(Console.ReadLine());

        if (f < 6)
        {
            Console.WriteLine("Экономичный");
        }
        else if (f <= 10)
        {
            Console.WriteLine("Средний");
        }
        else
        {
            Console.WriteLine("Прожорливый");
        }
    }

    // 99
    static void Task99()
    {
        Console.Write("Введите количество страниц: ");
        int p = int.Parse(Console.ReadLine());

        if (p < 48)
        {
            Console.WriteLine("Брошюра");
        }
        else if (p <= 150)
        {
            Console.WriteLine("Повесть");
        }
        else if (p <= 600)
        {
            Console.WriteLine("Роман");
        }
        else
        {
            Console.WriteLine("Фолиант");
        }
    }

    // 100
    static void Task100()
    {
        Console.Write("Введите число: ");
        double x = double.Parse(Console.ReadLine());

        if ((x >= 0 && x <= 10) || (x >= 20 && x <= 30) || (x >= 50 && x <= 100))
        {
            Console.WriteLine("Попадает в один из интервалов");
        }
        else
        {
            Console.WriteLine("Не попадает ни в один интервал");
        }
    }


    // 101
    static void Task101()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 3 == 0 && num % 5 == 0)
        {
            Console.WriteLine("Делится на 3 и на 5");
        }
        else
        {
            Console.WriteLine("Не делится одновременно на 3 и на 5");
        }
    }

    // 102
    static void Task102()
    {
        Console.Write("Введите сторону A: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите сторону B: ");
        double b = double.Parse(Console.ReadLine());
        Console.Write("Введите сторону C: ");
        double c = double.Parse(Console.ReadLine());

        if (a + b > c && a + c > b && b + c > a)
        {
            Console.WriteLine("Треугольник существует");
        }
        else
        {
            Console.WriteLine("Треугольник не существует");
        }
    }

    // 103
    static void Task103()
    {
        Console.Write("Введите номер месяца (1-12): ");
        int month = int.Parse(Console.ReadLine());

        if (month == 12 || month == 1 || month == 2)
        {
            Console.WriteLine("Зима");
        }
        else if (month >= 3 && month <= 5)
        {
            Console.WriteLine("Весна");
        }
        else if (month >= 6 && month <= 8)
        {
            Console.WriteLine("Лето");
        }
        else if (month >= 9 && month <= 11)
        {
            Console.WriteLine("Осень");
        }
        else
        {
            Console.WriteLine("Неверный номер месяца");
        }
    }

    // 104
    static void Task104()
    {
        Console.Write("Введите год: ");
        int year = int.Parse(Console.ReadLine());

        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0))
        {
            Console.WriteLine("Високосный год");
        }
        else
        {
            Console.WriteLine("Обычный год");
        }
    }

    // 105
    static void Task105()
    {
        Console.Write("Введите сумму покупки: ");
        double total = double.Parse(Console.ReadLine());

        if (total > 5000)
        {
            total *= 0.90;
        }
        else if (total > 1000)
        {
            total *= 0.95;
        }

        Console.WriteLine("Итоговая сумма: " + total);
    }

    // 106
    static void Task106()
    {
        Console.Write("Введите одну букву: ");
        char ch = char.ToLower(char.Parse(Console.ReadLine()));

        if ("аеёиоуыэюяaeiou".Contains(ch))
        {
            Console.WriteLine("Гласная буква");
        }
        else
        {
            Console.WriteLine("Согласная или иной символ");
        }
    }

    // 107
    static void Task107()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());
        Console.Write("Введите число C: ");
        int c = int.Parse(Console.ReadLine());

        if ((a >= b && a <= c) || (a <= b && a >= c))
        {
            Console.WriteLine("Среднее: " + a);
        }
        else if ((b >= a && b <= c) || (b <= a && b >= c))
        {
            Console.WriteLine("Среднее: " + b);
        }
        else
        {
            Console.WriteLine("Среднее: " + c);
        }
    }

    // 108
    static void Task108()
    {
        Console.Write("Введите четырехзначное число: ");
        int num = Math.Abs(int.Parse(Console.ReadLine()));

        int d1 = num / 1000;
        int d2 = (num / 100) % 10;
        int d3 = (num / 10) % 10;
        int d4 = num % 10;

        if (d1 == d4 && d2 == d3)
        {
            Console.WriteLine("Палиндром");
        }
        else
        {
            Console.WriteLine("Не палиндром");
        }
    }

    // 109
    static void Task109()
    {
        Console.Write("Введите процент выполнения (0-100): ");
        double p = double.Parse(Console.ReadLine());

        if (p >= 85)
        {
            Console.WriteLine("Отлично");
        }
        else if (p >= 70)
        {
            Console.WriteLine("Хорошо");
        }
        else if (p >= 50)
        {
            Console.WriteLine("Удовлетворительно");
        }
        else
        {
            Console.WriteLine("Неудовлетворительно");
        }
    }

    // 110
    static void Task110()
    {
        Console.Write("Введите доход: ");
        double income = double.Parse(Console.ReadLine());

        if (income <= 10000)
        {
            Console.WriteLine("Ставка налога: 0%");
        }
        else if (income <= 50000)
        {
            Console.WriteLine("Ставка налога: 10%");
        }
        else
        {
            Console.WriteLine("Ставка налога: 20%");
        }
    }

    // 111
    static void Task111()
    {
        Console.Write("Введите температуру: ");
        double t = double.Parse(Console.ReadLine());

        if (t <= 0)
        {
            Console.WriteLine("Твердое состояние");
        }
        else if (t < 100)
        {
            Console.WriteLine("Жидкое состояние");
        }
        else
        {
            Console.WriteLine("Газообразное состояние");
        }
    }

    // 112
    static void Task112()
    {
        Console.Write("Введите X: ");
        double x = double.Parse(Console.ReadLine());
        Console.Write("Введите Y: ");
        double y = double.Parse(Console.ReadLine());
        Console.Write("Введите радиус R: ");
        double r = double.Parse(Console.ReadLine());

        if (x * x + y * y <= r * r)
        {
            Console.WriteLine("Точка внутри окружности");
        }
        else
        {
            Console.WriteLine("Точка вне окружности");
        }
    }

    // 113
    static void Task113()
    {
        Console.Write("Введите X: ");
        double x = double.Parse(Console.ReadLine());
        Console.Write("Введите Y: ");
        double y = double.Parse(Console.ReadLine());

        if (x > 0 && y > 0)
        {
            Console.WriteLine("1 четверть");
        }
        else if (x < 0 && y > 0)
        {
            Console.WriteLine("2 четверть");
        }
        else if (x < 0 && y < 0)
        {
            Console.WriteLine("3 четверть");
        }
        else if (x > 0 && y < 0)
        {
            Console.WriteLine("4 четверть");
        }
        else
        {
            Console.WriteLine("На оси координат");
        }
    }

    // 114
    static void Task114()
    {
        Console.Write("Введите час (0-23): ");
        int h = int.Parse(Console.ReadLine());

        if (h == 0)
        {
            Console.WriteLine("12 AM");
        }
        else if (h < 12)
        {
            Console.WriteLine(h + " AM");
        }
        else if (h == 12)
        {
            Console.WriteLine("12 PM");
        }
        else
        {
            Console.WriteLine((h - 12) + " PM");
        }
    }

    // 115
    static void Task115()
    {
        Console.Write("Введите номер месяца (1-12): ");
        int m = int.Parse(Console.ReadLine());

        if (m == 2)
        {
            Console.WriteLine("28 или 29 дней");
        }
        else if (m == 4 || m == 6 || m == 9 || m == 11)
        {
            Console.WriteLine("30 дней");
        }
        else if (m >= 1 && m <= 12)
        {
            Console.WriteLine("31 день");
        }
        else
        {
            Console.WriteLine("Неверный номер месяца");
        }
    }

    // 116
    static void Task116()
    {
        Console.Write("Введите расход электроэнергии (кВт·ч): ");
        double kwh = double.Parse(Console.ReadLine());
        double bill;

        if (kwh <= 100)
        {
            bill = kwh * 3.5;
        }
        else
        {
            bill = 100 * 3.5 + (kwh - 100) * 5.0;
        }

        Console.WriteLine("К оплате: " + bill + " руб.");
    }

    // 117
    static void Task117()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();

        if (string.IsNullOrWhiteSpace(str))
        {
            Console.WriteLine("Строка пустая или состоит из пробелов");
        }
        else
        {
            Console.WriteLine("Строка содержит текст");
        }
    }

    // 118
    static void Task118()
    {
        Console.Write("Введите номер дня недели (1-7): ");
        int day = int.Parse(Console.ReadLine());

        if (day >= 1 && day <= 5)
        {
            Console.WriteLine("Рабочий день");
        }
        else if (day == 6 || day == 7)
        {
            Console.WriteLine("Выходной день");
        }
        else
        {
            Console.WriteLine("Некорректный день");
        }
    }

    // 119
    static void Task119()
    {
        Console.Write("Введите вашу скорость (км/ч): ");
        double speed = double.Parse(Console.ReadLine());

        if (speed <= 60)
        {
            Console.WriteLine("Без штрафа");
        }
        else if (speed <= 80)
        {
            Console.WriteLine("Штраф: 500 руб.");
        }
        else
        {
            Console.WriteLine("Штраф: 1500 руб.");
        }
    }

    // 120
    static void Task120()
    {
        Console.Write("Введите коэффициент A: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите коэффициент B: ");
        double b = double.Parse(Console.ReadLine());
        Console.Write("Введите коэффициент C: ");
        double c = double.Parse(Console.ReadLine());

        double d = b * b - 4 * a * c;

        if (d > 0)
        {
            Console.WriteLine("Уравнение имеет 2 корня");
        }
        else if (d == 0)
        {
            Console.WriteLine("Уравнение имеет 1 корень");
        }
        else
        {
            Console.WriteLine("Уравнение не имеет действительных корней");
        }
    }

    // 121
    static void Task121()
    {
        Console.Write("Введите N: ");
        int n = int.Parse(Console.ReadLine());
        int sum = 0;

        for (int i = 1; i <= n; i++)
        {
            sum += i;
        }

        Console.WriteLine("Сумма от 1 до " + n + " равна: " + sum);
    }

    // 122
    static void Task122()
    {
        Console.Write("Введите N: ");
        int n = int.Parse(Console.ReadLine());

        for (int i = 1; i <= n; i++)
        {
            Console.Write(i + " ");
        }
        Console.WriteLine();
    }

    // 123
    static void Task123()
    {
        Console.Write("Введите N: ");
        int n = int.Parse(Console.ReadLine());

        for (int i = 2; i <= n; i += 2)
        {
            Console.Write(i + " ");
        }
        Console.WriteLine();
    }

    // 124
    static void Task124()
    {
        Console.Write("Введите N: ");
        int n = int.Parse(Console.ReadLine());
        long fact = 1;

        for (int i = 1; i <= n; i++)
        {
            fact *= i;
        }

        Console.WriteLine("Факториал: " + fact);
    }

    // 125
    static void Task125()
    {
        Console.Write("Введите число: ");
        int n = int.Parse(Console.ReadLine());

        for (int i = 1; i <= 10; i++)
        {
            Console.WriteLine(n + " * " + i + " = " + (n * i));
        }
    }

    // 126
    static void Task126()
    {
        Console.Write("Введите целое число: ");
        int num = Math.Abs(int.Parse(Console.ReadLine()));
        int count = 0;

        if (num == 0)
        {
            count = 1;
        }
        else
        {
            while (num > 0)
            {
                num /= 10;
                count++;
            }
        }

        Console.WriteLine("Количество цифр: " + count);
    }

    // 127
    static void Task127()
    {
        Console.Write("Введите целое число: ");
        int num = Math.Abs(int.Parse(Console.ReadLine()));
        int sum = 0;

        while (num > 0)
        {
            sum += num % 10;
            num /= 10;
        }

        Console.WriteLine("Сумма цифр: " + sum);
    }

    // 128
    static void Task128()
    {
        Console.Write("Введите целое число: ");
        int num = int.Parse(Console.ReadLine());
        int rev = 0;

        while (num != 0)
        {
            rev = rev * 10 + num % 10;
            num /= 10;
        }

        Console.WriteLine("Реверс числа: " + rev);
    }

    // 129
    static void Task129()
    {
        Console.Write("Введите целое число: ");
        int n = int.Parse(Console.ReadLine());
        bool isPrime = n > 1;

        for (int i = 2; i * i <= n; i++)
        {
            if (n % i == 0)
            {
                isPrime = false;
                break;
            }
        }

        if (isPrime)
        {
            Console.WriteLine("Простое число");
        }
        else
        {
            Console.WriteLine("Не простое число");
        }
    }

    // 130
    static void Task130()
    {
        Console.Write("Введите количество элементов Фибоначчи: ");
        int n = int.Parse(Console.ReadLine());

        int a = 0, b = 1;

        for (int i = 0; i < n; i++)
        {
            Console.Write(a + " ");
            int temp = a + b;
            a = b;
            b = temp;
        }
        Console.WriteLine();
    }

    // 131
    static void Task131()
    {
        Console.Write("Введите основание A: ");
        double a = double.Parse(Console.ReadLine());
        Console.Write("Введите показатель B: ");
        int b = int.Parse(Console.ReadLine());

        double result = Math.Pow(a, b);
        Console.WriteLine("Результат: " + result);
    }

    // 132
    static void Task132()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());

        while (b != 0)
        {
            int temp = b;
            b = a % b;
            a = temp;
        }

        Console.WriteLine("НОД: " + a);
    }

    // 133
    static void Task133()
    {
        Console.Write("Введите число A: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Введите число B: ");
        int b = int.Parse(Console.ReadLine());

        int origA = a, origB = b;

        while (b != 0)
        {
            int temp = b;
            b = a % b;
            a = temp;
        }

        int lcm = (origA * origB) / a;
        Console.WriteLine("НОК: " + lcm);
    }

    // 134
    static void Task134()
    {
        Console.Write("Введите размер квадрата N: ");
        int n = int.Parse(Console.ReadLine());

        for (int i = 0; i < n; i++)
        {
            for (int j = 0; j < n; j++)
            {
                Console.Write("* ");
            }
            Console.WriteLine();
        }
    }

    // 135
    static void Task135()
    {
        Console.Write("Введите высоту треугольника N: ");
        int n = int.Parse(Console.ReadLine());

        for (int i = 1; i <= n; i++)
        {
            for (int j = 0; j < i; j++)
            {
                Console.Write("* ");
            }
            Console.WriteLine();
        }
    }

    // 136
    static void Task136()
    {
        int[] arr = { 1, 2, 3, 4, 5 };
        int sum = 0;

        for (int i = 0; i < arr.Length; i++)
        {
            sum += arr[i];
        }

        Console.WriteLine("Сумма элементов массива: " + sum);
    }

    // 137
    static void Task137()
    {
        int[] arr = { 3, 7, 2, 9, 4 };
        int max = arr[0];

        for (int i = 1; i < arr.Length; i++)
        {
            if (arr[i] > max)
            {
                max = arr[i];
            }
        }

        Console.WriteLine("Максимум: " + max);
    }

    // 138
    static void Task138()
    {
        int[] arr = { 3, 7, 2, 9, 4 };
        int min = arr[0];

        for (int i = 1; i < arr.Length; i++)
        {
            if (arr[i] < min)
            {
                min = arr[i];
            }
        }

        Console.WriteLine("Минимум: " + min);
    }

    // 139
    static void Task139()
    {
        int[] arr = { -1, 3, 0, -5, 8, 4 };
        int count = 0;

        for (int i = 0; i < arr.Length; i++)
        {
            if (arr[i] > 0)
            {
                count++;
            }
        }

        Console.WriteLine("Положительных элементов: " + count);
    }

    // 140
    static void Task140()
    {
        int[] arr = { 10, 20, 30, 40, 50 };
        double sum = 0;

        for (int i = 0; i < arr.Length; i++)
        {
            sum += arr[i];
        }

        Console.WriteLine("Среднее арифметическое: " + (sum / arr.Length));
    }

    // 141
    static void Task141()
    {
        int[] arr = { 5, 12, 8, 19, 3 };
        Console.Write("Введите число для поиска: ");
        int target = int.Parse(Console.ReadLine());
        bool found = false;

        for (int i = 0; i < arr.Length; i++)
        {
            if (arr[i] == target)
            {
                found = true;
                break;
            }
        }

        if (found)
        {
            Console.WriteLine("Элемент найден в массиве");
        }
        else
        {
            Console.WriteLine("Элемент не найден");
        }
    }

    // 142
    static void Task142()
    {
        int[] arr = { 1, 2, 3, 4, 5 };

        for (int i = arr.Length - 1; i >= 0; i--)
        {
            Console.Write(arr[i] + " ");
        }
        Console.WriteLine();
    }

    // 143
    static void Task143()
    {
        int[] arr = { 5, 2, 8, 1, 4 };
        Array.Sort(arr);

        Console.WriteLine("Отсортированный массив: " + string.Join(", ", arr));
    }

    // 144
    static void Task144()
    {
        int[] arr = { 1, 3, 3, 2, 3, 4, 1 };
        Console.Write("Введите искомый элемент: ");
        int item = int.Parse(Console.ReadLine());
        int count = 0;

        for (int i = 0; i < arr.Length; i++)
        {
            if (arr[i] == item)
            {
                count++;
            }
        }

        Console.WriteLine("Встречается раз: " + count);
    }

    // 145
    static void Task145()
    {
        int[] arr = { 1, 3, 5, 7, 9 };
        bool sorted = true;

        for (int i = 0; i < arr.Length - 1; i++)
        {
            if (arr[i] > arr[i + 1])
            {
                sorted = false;
                break;
            }
        }

        if (sorted)
        {
            Console.WriteLine("Массив отсортирован по возрастанию");
        }
        else
        {
            Console.WriteLine("Массив не отсортирован");
        }
    }

    // 146
    static void Task146()
    {
        int[] arr = { -2, 5, -8, 3, -1 };

        for (int i = 0; i < arr.Length; i++)
        {
            if (arr[i] < 0)
            {
                arr[i] = 0;
            }
        }

        Console.WriteLine("Результат: " + string.Join(", ", arr));
    }

    // 147
    static void Task147()
    {
        int[] arr = { 10, 40, 20, 50, 30 };
        int max = int.MinValue;
        int secondMax = int.MinValue;

        for (int i = 0; i < arr.Length; i++)
        {
            if (arr[i] > max)
            {
                secondMax = max;
                max = arr[i];
            }
            else if (arr[i] > secondMax && arr[i] != max)
            {
                secondMax = arr[i];
            }
        }

        Console.WriteLine("Второй по величине элемент: " + secondMax);
    }

    // 148
    static void Task148()
    {
        int[] source = { 10, 20, 30, 40 };
        int[] target = new int[source.Length];

        for (int i = 0; i < source.Length; i++)
        {
            target[i] = source[i];
        }

        Console.WriteLine("Скопированный массив: " + string.Join(", ", target));
    }

    // 149
    static void Task149()
    {
        int[] arr1 = { 1, 2, 3 };
        int[] arr2 = { 4, 5, 6 };
        int[] merged = new int[arr1.Length + arr2.Length];

        for (int i = 0; i < arr1.Length; i++)
        {
            merged[i] = arr1[i];
        }
        for (int i = 0; i < arr2.Length; i++)
        {
            merged[arr1.Length + i] = arr2[i];
        }

        Console.WriteLine("Объединенный массив: " + string.Join(", ", merged));
    }

    // 150
    static void Task150()
    {
        int[,] matrix = {
            { 1, 2, 3 },
            { 4, 5, 6 }
        };
        int sum = 0;

        for (int i = 0; i < matrix.GetLength(0); i++)
        {
            for (int j = 0; j < matrix.GetLength(1); j++)
            {
                sum += matrix[i, j];
            }
        }

        Console.WriteLine("Сумма элементов матрицы 2D: " + sum);
    }


    // 151
    static void Task151()
    {
        int[,] matrix = {
            { 1, 8, 3 },
            { 4, 2, 6 }
        };
        int max = matrix[0, 0];

        for (int i = 0; i < matrix.GetLength(0); i++)
        {
            for (int j = 0; j < matrix.GetLength(1); j++)
            {
                if (matrix[i, j] > max)
                {
                    max = matrix[i, j];
                }
            }
        }

        Console.WriteLine("Максимум в матрице: " + max);
    }

    // 152
    static void Task152()
    {
        int[,] matrix = {
            { 5, 8, 3 },
            { 4, 1, 6 }
        };
        int min = matrix[0, 0];

        for (int i = 0; i < matrix.GetLength(0); i++)
        {
            for (int j = 0; j < matrix.GetLength(1); j++)
            {
                if (matrix[i, j] < min)
                {
                    min = matrix[i, j];
                }
            }
        }

        Console.WriteLine("Минимум в матрице: " + min);
    }

    // 153
    static void Task153()
    {
        int[,] matrix = {
            { 1, 2, 3 },
            { 4, 5, 6 },
            { 7, 8, 9 }
        };
        int sum = 0;

        for (int i = 0; i < matrix.GetLength(0); i++)
        {
            sum += matrix[i, i];
        }

        Console.WriteLine("Сумма главной диагонали: " + sum);
    }

    // 154
    static void Task154()
    {
        int[,] matrix = {
            { 1, 2 },
            { 3, 4 },
            { 5, 6 }
        };
        int rows = matrix.GetLength(0);
        int cols = matrix.GetLength(1);
        int[,] transposed = new int[cols, rows];

        for (int i = 0; i < rows; i++)
        {
            for (int j = 0; j < cols; j++)
            {
                transposed[j, i] = matrix[i, j];
            }
        }

        Console.WriteLine("Транспонированная матрица:");
        for (int i = 0; i < cols; i++)
        {
            for (int j = 0; j < rows; j++)
            {
                Console.Write(transposed[i, j] + " ");
            }
            Console.WriteLine();
        }
    }

    // 155
    static void Task155()
    {
        int[,] matrix = {
            { 0, 2, 0 },
            { 4, 0, 6 }
        };
        int count = 0;

        for (int i = 0; i < matrix.GetLength(0); i++)
        {
            for (int j = 0; j < matrix.GetLength(1); j++)
            {
                if (matrix[i, j] != 0)
                {
                    count++;
                }
            }
        }

        Console.WriteLine("Количество ненулевых элементов: " + count);
    }

    // 156
    static void Task156()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();

        Console.WriteLine("Длина строки: " + str.Length);
    }

    // 157
    static void Task157()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();
        char[] arr = str.ToCharArray();
        Array.Reverse(arr);

        Console.WriteLine("Перевернутая строка: " + new string(arr));
    }

    // 158
    static void Task158()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine().ToLower();
        int count = 0;

        for (int i = 0; i < str.Length; i++)
        {
            if ("аеёиоуыэюяaeiou".Contains(str[i]))
            {
                count++;
            }
        }

        Console.WriteLine("Количество гласных: " + count);
    }

    // 159
    static void Task159()
    {
        Console.Write("Введите слово: ");
        string word = Console.ReadLine().ToLower();
        char[] arr = word.ToCharArray();
        Array.Reverse(arr);
        string rev = new string(arr);

        if (word == rev)
        {
            Console.WriteLine("Слово является палиндромом");
        }
        else
        {
            Console.WriteLine("Слово не является палиндромом");
        }
    }

    // 160
    static void Task160()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();

        Console.WriteLine("В верхнем регистре: " + str.ToUpper());
    }

    // 161
    static void Task161()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();

        Console.WriteLine("В нижнем регистре: " + str.ToLower());
    }

    // 162
    static void Task162()
    {
        Console.Write("Введите предложение: ");
        string text = Console.ReadLine().Trim();

        if (string.IsNullOrEmpty(text))
        {
            Console.WriteLine("Количество слов: 0");
        }
        else
        {
            string[] words = text.Split(new char[] { ' ' }, StringSplitOptions.RemoveEmptyEntries);
            Console.WriteLine("Количество слов: " + words.Length);
        }
    }

    // 163
    static void Task163()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();

        string result = str.Replace('a', 'o').Replace('а', 'о');
        Console.WriteLine("Результат замены: " + result);
    }

    // 164
    static void Task164()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();
        Console.Write("Введите подстроку: ");
        string sub = Console.ReadLine();

        if (str.StartsWith(sub))
        {
            Console.WriteLine("Да, начинается с этой подстроки");
        }
        else
        {
            Console.WriteLine("Нет, не начинается");
        }
    }

    // 165
    static void Task165()
    {
        Console.Write("Введите текст: ");
        string text = Console.ReadLine();
        Console.Write("Введите искомое слово: ");
        string word = Console.ReadLine();

        if (text.Contains(word))
        {
            Console.WriteLine("Текст содержит искомое слово");
        }
        else
        {
            Console.WriteLine("Слово не найдено");
        }
    }

    // 166
    static void Task166()
    {
        Console.Write("Введите строку с пробелами: ");
        string str = Console.ReadLine();

        string result = str.Trim();
        Console.WriteLine("Результат: '" + result + "'");
    }

    // 167
    static void Task167()
    {
        Console.Write("Введите строку: ");
        string str = Console.ReadLine();
        Console.Write("Введите символ: ");
        char ch = char.Parse(Console.ReadLine());

        int index = str.IndexOf(ch);
        if (index != -1)
        {
            Console.WriteLine("Индекс первого вхождения: " + index);
        }
        else
        {
            Console.WriteLine("Символ не найден");
        }
    }

    // 168
    static void Task168()
    {
        Console.Write("Введите элементы через запятую: ");
        string str = Console.ReadLine();

        string[] parts = str.Split(',');
        Console.WriteLine("Разделенные элементы:");
        for (int i = 0; i < parts.Length; i++)
        {
            Console.WriteLine(parts[i].Trim());
        }
    }

    // 169
    static void Task169()
    {
        Console.Write("Введите первую строку: ");
        string str1 = Console.ReadLine();
        Console.Write("Введите вторую строку: ");
        string str2 = Console.ReadLine();

        string result = string.Concat(str1, " ", str2);
        Console.WriteLine("Результат объединения: " + result);
    }

    // 170
    static void Task170()
    {
        Console.Write("Введите первую строку: ");
        string str1 = Console.ReadLine();
        Console.Write("Введите вторую строку: ");
        string str2 = Console.ReadLine();

        if (string.Equals(str1, str2, StringComparison.OrdinalIgnoreCase))
        {
            Console.WriteLine("Строки равны без учета регистра");
        }
        else
        {
            Console.WriteLine("Строки различаются");
        }
    }

    // 171
    static int AddNumbers(int a, int b)
    {
        return a + b;
    }

    static void Task171()
    {
        int sum = AddNumbers(15, 25);
        Console.WriteLine("Сумма чисел (метод): " + sum);
    }

    // 172
    static long GetFactorial(int n)
    {
        long f = 1;
        for (int i = 1; i <= n; i++)
        {
            f *= i;
        }
        return f;
    }

    static void Task172()
    {
        long fact = GetFactorial(5);
        Console.WriteLine("Факториал 5 (метод): " + fact);
    }

    // 173
    static bool IsEven(int number)
    {
        return number % 2 == 0;
    }

    static void Task173()
    {
        bool result = IsEven(8);
        Console.WriteLine("Число 8 четное? " + result);
    }

    // 174
    static int GetMax(int a, int b)
    {
        return a > b ? a : b;
    }

    static void Task174()
    {
        int max = GetMax(42, 18);
        Console.WriteLine("Максимум (метод): " + max);
    }

    // 175
    static double Power(double baseNum, int exp)
    {
        return Math.Pow(baseNum, exp);
    }

    static void Task175()
    {
        double res = Power(2, 10);
        Console.WriteLine("2 в степени 10: " + res);
    }

    // 176
    static string ReverseString(string s)
    {
        char[] arr = s.ToCharArray();
        Array.Reverse(arr);
        return new string(arr);
    }

    static void Task176()
    {
        string rev = ReverseString("Hello");
        Console.WriteLine("Реверс строки: " + rev);
    }

    // 177
    static int SumArray(int[] arr)
    {
        int s = 0;
        for (int i = 0; i < arr.Length; i++)
        {
            s += arr[i];
        }
        return s;
    }

    static void Task177()
    {
        int[] data = { 1, 2, 3, 4, 5 };
        Console.WriteLine("Сумма элементов массива: " + SumArray(data));
    }

    // 178
    static double GetAverage(int[] arr)
    {
        double s = 0;
        for (int i = 0; i < arr.Length; i++)
        {
            s += arr[i];
        }
        return s / arr.Length;
    }

    static void Task178()
    {
        int[] data = { 10, 20, 30, 40 };
        Console.WriteLine("Среднее арифметическое: " + GetAverage(data));
    }

    // 179
    static bool CheckPrime(int n)
    {
        if (n <= 1)
        {
            return false;
        }
        for (int i = 2; i * i <= n; i++)
        {
            if (n % i == 0)
            {
                return false;
            }
        }
        return true;
    }

    static void Task179()
    {
        Console.WriteLine("7 - простое число? " + CheckPrime(7));
    }

    // 180
    static void Swap(ref int a, ref int b)
    {
        int temp = a;
        a = b;
        b = temp;
    }

    static void Task180()
    {
        int x = 5, y = 10;
        Swap(ref x, ref y);
        Console.WriteLine("После обмена: x = " + x + ", y = " + y);
    }

    // 181
    static void Task181()
    {
        List<int> list = new List<int> { 10, 20, 30 };
        list.Add(40);

        Console.WriteLine("Элементы списка: " + string.Join(", ", list));
    }

    // 182
    static void Task182()
    {
        List<int> list = new List<int> { 10, 20, 30, 40 };
        list.Remove(20);

        Console.WriteLine("После удаления 20: " + string.Join(", ", list));
    }

    // 183
    static void Task183()
    {
        List<string> cities = new List<string> { "Москва", "Минск", "Астана" };
        bool contains = cities.Contains("Минск");

        Console.WriteLine("Содержит 'Минск': " + contains);
    }

    // 184
    static void Task184()
    {
        List<int> list = new List<int> { 5, 2, 9, 1, 3 };
        list.Sort();

        Console.WriteLine("Отсортированный список: " + string.Join(", ", list));
    }

    // 185
    static void Task185()
    {
        List<int> list = new List<int> { 10, 15, 20 };
        int sum = 0;

        for (int i = 0; i < list.Count; i++)
        {
            sum += list[i];
        }

        Console.WriteLine("Сумма списка: " + sum);
    }

    // 186
    static void Task186()
    {
        List<string> fruits = new List<string> { "Яблоко", "Банан", "Груша" };

        for (int i = 0; i < fruits.Count; i++)
        {
            Console.WriteLine((i + 1) + ". " + fruits[i]);
        }
    }

    // 187
    static void Task187()
    {
        List<int> numbers = new List<int> { 1, 2, 3, 4, 5, 6, 7, 8 };
        List<int> evens = new List<int>();

        for (int i = 0; i < numbers.Count; i++)
        {
            if (numbers[i] % 2 == 0)
            {
                evens.Add(numbers[i]);
            }
        }

        Console.WriteLine("Четные числа: " + string.Join(", ", evens));
    }

    // 188
    static void Task188()
    {
        List<int> list = new List<int> { 12, 45, 67, 23, 9 };
        int max = list[0];

        for (int i = 1; i < list.Count; i++)
        {
            if (list[i] > max)
            {
                max = list[i];
            }
        }

        Console.WriteLine("Максимум в списке: " + max);
    }

    // 189
    static void Task189()
    {
        List<int> list = new List<int> { 1, 2, 3, 4 };
        list.Clear();

        Console.WriteLine("Количество элементов после очистки: " + list.Count);
    }

    // 190
    static void Task190()
    {
        List<double> list = new List<double> { 1.5, 2.7, 3.8 };

        Console.WriteLine("Размер списка: " + list.Count);
    }

    // 191
    class Person
    {
        public string Name;
        public int Age;

        public void DisplayInfo()
        {
            Console.WriteLine("Имя: " + Name + ", Возраст: " + Age);
        }
    }

    static void Task191()
    {
        Person p = new Person { Name = "Иван", Age = 25 };
        p.DisplayInfo();
    }

    // 192
    class Rectangle
    {
        public double Width;
        public double Height;

        public double GetArea()
        {
            return Width * Height;
        }
    }

    static void Task192()
    {
        Rectangle rect = new Rectangle { Width = 5, Height = 10 };
        Console.WriteLine("Площадь прямоугольника: " + rect.GetArea());
    }

    // 193
    class Circle
    {
        public double Radius;

        public double GetCircumference()
        {
            return 2 * Math.PI * Radius;
        }
    }

    static void Task193()
    {
        Circle c = new Circle { Radius = 4 };
        Console.WriteLine("Длина окружности: " + c.GetCircumference());
    }

    // 194
    class BankAccount
    {
        public double Balance;

        public void Deposit(double amount)
        {
            Balance += amount;
        }

        public void Withdraw(double amount)
        {
            if (amount <= Balance)
            {
                Balance -= amount;
            }
            else
            {
                Console.WriteLine("Недостаточно средств");
            }
        }
    }

    static void Task194()
    {
        BankAccount acc = new BankAccount { Balance = 1000 };
        acc.Deposit(500);
        acc.Withdraw(200);
        Console.WriteLine("Текущий баланс: " + acc.Balance);
    }

    // 195
    class Car
    {
        public string Brand;
        public bool IsRunning;

        public void StartEngine()
        {
            IsRunning = true;
            Console.WriteLine(Brand + ": Двигатель запущен");
        }
    }

    static void Task195()
    {
        Car myCar = new Car { Brand = "Toyota" };
        myCar.StartEngine();
    }

    // 196
    class Student
    {
        public string Name;
        public int Grade;

        public bool IsPassed()
        {
            return Grade >= 60;
        }
    }

    static void Task196()
    {
        Student s = new Student { Name = "Алексей", Grade = 75 };
        Console.WriteLine(s.Name + " сдал экзамен? " + s.IsPassed());
    }

    // 197
    class Book
    {
        public string Title;
        public string Author;

        public void GetInfo()
        {
            Console.WriteLine("Книга: '" + Title + "', Автор: " + Author);
        }
    }

    static void Task197()
    {
        Book b = new Book { Title = "1984", Author = "Джордж Оруэлл" };
        b.GetInfo();
    }

    // 198
    class Calculator
    {
        public double Multiply(double a, double b)
        {
            return a * b;
        }

        public double Divide(double a, double b)
        {
            if (b != 0)
            {
                return a / b;
            }
            Console.WriteLine("Деление на ноль!");
            return 0;
        }
    }

    static void Task198()
    {
        Calculator calc = new Calculator();
        Console.WriteLine("Умножение: " + calc.Multiply(6, 7));
    }

    // 199
    class Point
    {
        public double X;
        public double Y;

        public double DistanceToOrigin()
        {
            return Math.Sqrt(X * X + Y * Y);
        }
    }

    static void Task199()
    {
        Point pt = new Point { X = 3, Y = 4 };
        Console.WriteLine("Расстояние до начала координат: " + pt.DistanceToOrigin());
    }

    // 200
    class Dog
    {
        public string Name;

        public void Bark()
        {
            Console.WriteLine(Name + " говорит: Гав-гав!");
        }
    }

    static void Task200()
    {
        Dog dog = new Dog { Name = "Шарик" };
        dog.Bark();
    }
}