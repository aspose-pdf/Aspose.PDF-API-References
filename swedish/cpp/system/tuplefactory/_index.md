---
title: "System::TupleFactory class"
linktitle: "TupleFactory"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TupleFactory class. Tillhandahåller statiska metoder för att skapa tuple-objekt i C++."
type: docs
weight: 6800
url: /sv/cpp/system/tuplefactory/
---
## TupleFactory class


Tillhandahåller statiska metoder för att skapa tupel‑objekt.

```cpp
class TupleFactory
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)(Args...) | Skapar ett nytt tuple-objekt. |
| static [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Skapar en ny 8-tuple. Det åttonde elementet lagras i [Tuple](../tuple/). |
## Anmärkningar



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

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
