---
title: "System::Random класс"
linktitle: "Random"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Random class. Представляет генератор псевдослучайных чисел. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 5400
url: /ru/cpp/system/random/
---
## Random class


Представляет генератор псевдослучайных чисел. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Random : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [IsNull](./isnull/)() const | Всегда возвращает false. |
| virtual [Next](./next/)() | Возвращает неотрицательное случайное число, меньше максимального значения int32. |
| virtual [Next](./next/)(int32_t) | Возвращает неотрицательное случайное число, меньше указанного максимума. |
| virtual [Next](./next/)(int32_t, int32_t) | Возвращает случайное число в указанном диапазоне. |
| virtual [NextBytes](./nextbytes/)(const ArrayPtr\<uint8_t\>\&) | Заполняет элементы указанного массива байтов случайными числами. |
| virtual [NextDouble](./nextdouble/)() | Возвращает случайное число в диапазоне от 0.0 до 1.0. |
| [Random](./random/)() | Инициализирует новый экземпляр, используя зависящее от времени значение seed по умолчанию. |
| [Random](./random/)(int32_t) | Инициализирует новый экземпляр класса [System.Random](./), используя указанное значение seed. |
## Примечания



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Получите случайный номер месяца и выведите его.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Заполните массив случайными числами.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Выведите массив.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
This code example produces the following output:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
