---
title: "System::Tuple klass"
linktitle: "Tuple"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Tuple klass. Klass som representerar en tupel-datastruktur. Maximalt antal objekt är 8 i C++."
type: docs
weight: 6700
url: /sv/cpp/system/tuple/
---
## Tuple class


Klass som representerar en tupel‑datastruktur. Maximalt antal element är 8.

```cpp
template<typename ...>class Tuple : public System::Runtime::CompilerServices::ITuple
```


| Parameter | Beskrivning |
| --- | --- |
| Argument | Typerna för tupelns element. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Avgör om det aktuella och det angivna objektet är identiska. |
| [get_Item](./get_item/)() const | Hämtar värdet på komponenten i [Tuple](./)-objektet. |
| [Tuple](./tuple/)(Args...) | Skapar ett tupelobjekt. |
## Anmärkningar



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

## Se även

* Class [ITuple](../../system.runtime.compilerservices/ituple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
