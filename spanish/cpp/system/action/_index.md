---
title: "System::Action typedef"
linktitle: "Action"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Action typedef. Tipo de delegado que hace referencia a métodos que no tienen valor de retorno en C++."
type: docs
weight: 9700
url: /es/cpp/system/action/
---
## Action typedef


Tipo de delegado que referencia métodos que no devuelven valor.

```cpp
using System::Action =  MulticastDelegate<void(Args...)>
```

## Observaciones



```cpp
#include <system/action.h>

using namespace System;

// La función que imprime la cadena pasada.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Crea una instancia de Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Llama a la acción.
  action(u"Hello, world!");

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
