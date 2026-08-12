---
title: "Класс System::Tuple"
linktitle: "Tuple"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Tuple. Класс, представляющий структуру данных кортежа. Максимальное количество элементов — 8 в C++."
type: docs
weight: 6700
url: /ru/cpp/system/tuple/
---
## Tuple class


Класс, представляющий структуру кортежа. Максимальное количество элементов — 8.

```cpp
template<typename ...>class Tuple : public System::Runtime::CompilerServices::ITuple
```


| Параметр | Описание |
| --- | --- |
| Аргументы | Типы элементов кортежа. |
## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Определяет, являются ли текущий и указанный объекты идентичными. |
| [get_Item](./get_item/)() const | Получает значение компонента объекта [Tuple](./). |
| [Tuple](./tuple/)(Args...) | Создаёт объект кортежа. |
## Примечания



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::MakeObject<System::Tuple<int, int, int>>(32, 16, 128);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
This code example produces the following output:
Item 1: 32
Item 2: 16
Item 3: 128
*/
```

## См. также

* Class [ITuple](../../system.runtime.compilerservices/ituple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
