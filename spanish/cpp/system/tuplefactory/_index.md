---
title: "System::TupleFactory clase"
linktitle: "TupleFactory"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TupleFactory clase. Proporciona métodos estáticos para crear objetos tuple en C++."
type: docs
weight: 6800
url: /es/cpp/system/tuplefactory/
---
## TupleFactory class


Proporciona métodos estáticos para crear objetos de tupla.

```cpp
class TupleFactory
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Create](./create/)(Args...) | Crea un nuevo objeto tuple. |
| static [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Crea un nuevo 8-tuple. El octavo elemento se almacena dentro de [Tuple](../tuple/). |
## Observaciones



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

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
