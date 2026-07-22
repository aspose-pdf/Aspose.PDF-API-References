---
title: "System::Predicate-typedef"
linktitle: "Predikat"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Predicate-typedef. Representerar en pekare till ett predikat – en anropbar entitet som accepterar ett enda argument och returnerar ett booleskt värde i C++."
type: docs
weight: 12900
url: /sv/cpp/system/predicate/
---
## Predicate typedef


Representerar en pekare till ett predikat – en anropbar entitet som accepterar ett enda argument och returnerar ett booleskt värde.

```cpp
using System::Predicate =  MulticastDelegate<bool(T)>
```

## Anmärkningar



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Fyll arrayen.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Skapa predikatet som returnerar ett array‑element som är större än 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Hitta det första elementet i arrayen med det skapade predikatet och skriv ut det.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
This code example produces the following output:
5
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
