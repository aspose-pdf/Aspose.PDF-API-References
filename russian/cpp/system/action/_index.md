---
title: "System::Action typedef"
linktitle: "Action"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Action typedef. Тип делегата, который ссылается на методы без возвращаемого значения в C++."
type: docs
weight: 9700
url: /ru/cpp/system/action/
---
## Action typedef


Тип делегата, ссылающийся на методы без возвращаемого значения.

```cpp
using System::Action =  MulticastDelegate<void(Args...)>
```

## Примечания



```cpp
#include <system/action.h>

using namespace System;

// Функция, выводящая переданную строку.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Создайте экземпляр Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Вызовите действие.
  action(u"Hello, world!");

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
