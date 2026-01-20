---
title: System::TupleFactory class
linktitle: TupleFactory
second_title: Aspose.PDF for C++ API Reference
description: 'System::TupleFactory class. Provides static methods for creating tuple objects in C++.'
type: docs
weight: 6500
url: /cpp/system/tuplefactory/
---
## TupleFactory class


Provides static methods for creating tuple objects.

```cpp
class TupleFactory
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)(Args...) | Creates a new tuple object. |
| static [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Creates a new 8-tuple. The 8th element is stored inside [Tuple](../tuple/). |
## Remarks



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

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
