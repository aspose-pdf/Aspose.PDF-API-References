---
title: "System::TupleFactory класс"
linktitle: "TupleFactory"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::TupleFactory класс. Предоставляет статические методы для создания объектов кортежей в C++."
type: docs
weight: 6800
url: /ru/cpp/system/tuplefactory/
---
## TupleFactory class


Предоставляет статические методы для создания объектов кортежа.

```cpp
class TupleFactory
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Create](./create/)(Args...) | Создаёт новый объект кортежа. |
| static [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Создаёт новый 8‑кортеж. 8‑й элемент хранится внутри [Tuple](../tuple/). |
## Примечания



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
This code example produces the following output:
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
