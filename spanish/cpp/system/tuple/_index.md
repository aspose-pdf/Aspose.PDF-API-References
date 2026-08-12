---
title: "System::Tuple clase"
linktitle: "Tuple"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Tuple clase. Clase que representa una estructura de datos de tupla. El número máximo de elementos es 8 en C++."
type: docs
weight: 6700
url: /es/cpp/system/tuple/
---
## Tuple class


Clase que representa una estructura de datos de tupla. El número máximo de elementos es 8.

```cpp
template<typename ...>class Tuple : public System::Runtime::CompilerServices::ITuple
```


| Parámetro | Descripción |
| --- | --- |
| Args | Los tipos de los elementos de la tupla. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Determina si el objeto actual y el objeto especificado son idénticos. |
| [get_Item](./get_item/)() const | Obtiene el valor del componente del objeto [Tuple](./). |
| [Tuple](./tuple/)(Args...) | Construye un objeto de tupla. |
## Observaciones



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

## Ver también

* Class [ITuple](../../system.runtime.compilerservices/ituple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
