---
title: "System::Nullable::Equals método"
linktitle: "Igual"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Nullable::Equals método. Determina si el valor representado por el objeto actual es igual al valor representado por el objeto Nullable especificado en C++."
type: docs
weight: 200
url: /es/cpp/system/nullable/equals/
---
## Nullable::Equals method


Determina si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](../) especificado.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](../) especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
