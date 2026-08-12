---
title: "typedef System::Predicate"
linktitle: "Predicate"
second_title: "Справочник API Aspose.PDF для C++"
description: "typedef System::Predicate. Представляет указатель на предикат — вызываемый объект, принимающий один аргумент и возвращающий значение типа bool в C++."
type: docs
weight: 12900
url: /ru/cpp/system/predicate/
---
## Predicate typedef


Представляет указатель на предикат — вызываемую сущность, принимающую один аргумент и возвращающую значение типа bool.

```cpp
using System::Predicate =  MulticastDelegate<bool(T)>
```

## Примечания



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Заполните массив.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Создайте предикат, который возвращает элемент массива, больший чем 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Найдите первый элемент массива, используя созданный предикат, и выведите его.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
This code example produces the following output:
5
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
