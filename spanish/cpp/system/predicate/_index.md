---
title: "System::Predicate typedef"
linktitle: "Predicado"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Predicate typedef. Representa un puntero a un predicado - una entidad invocable que acepta un único argumento y devuelve un valor bool en C++."
type: docs
weight: 12900
url: /es/cpp/system/predicate/
---
## Predicate typedef


Representa un puntero a un predicado - una entidad invocable que acepta un solo argumento y devuelve un valor booleano.

```cpp
using System::Predicate =  MulticastDelegate<bool(T)>
```

## Observaciones



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Llena el arreglo.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Crea el predicado que devuelve un elemento del arreglo que sea mayor que 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Encuentra el primer elemento del arreglo usando el predicado creado y imprímelo.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
This code example produces the following output:
5
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
