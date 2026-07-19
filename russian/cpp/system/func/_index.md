---
title: "System::Func class"
linktitle: "Func"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Func class. Делегат функции. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 2900
url: /ru/cpp/system/func/
---
## Func class


Делегат функции. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


| Параметр | Описание |
| --- | --- |
| Аргументы | Аргументы вызова, затем обязательный тип возвращаемого значения. |
## Методы

| Метод | Описание |
| --- | --- |
| [Func](./func/)() | Конструктор по умолчанию, создающий null-Func. |
| [Func](./func/)(T\&&) | Конструктор, который создает объект [Func](./) и присваивает ему значение (либо реальный обратный вызов, либо nullptr). |
| [Func](./func/)(const Func\&) | Конструктор копирования. |
| [Func](./func/)(Func\&&) | Конструктор перемещения. |
| [operator=](./operator=/)(const Func\&) | Копирующее присваивание. |
| [operator=](./operator=/)(Func\&&) | Перемещающее присваивание. |
| [~Func](./~func/)() | Деструктор. |
## Примечания



```cpp
#include "system/func.h"
#include <iostream>

// Эта функция принимает в качестве параметра экземпляр делегата System::Func.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Создайте экземпляр делегата System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Передайте созданный экземпляр в качестве аргумента функции.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
This code example produces the following output:
1
4
9
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
