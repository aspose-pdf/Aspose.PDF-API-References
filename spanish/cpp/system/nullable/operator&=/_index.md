---
title: "Método System::Nullable::operator&="
linktitle: "operator&="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Nullable::operator&=. Aplica operator&=() al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho en C++."
type: docs
weight: 1100
url: /es/cpp/system/nullable/operator&=/
---
## Nullable::operator&= method


Aplica [operator&=()](./) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El parámetro de plantilla para que SFINAE funcione. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | bool | Un valor booleano que se usa como valor del lado derecho del [operator&=()](./) aplicado al valor representado por el objeto actual. |

### ReturnValue

Una referencia al propio objeto.

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
