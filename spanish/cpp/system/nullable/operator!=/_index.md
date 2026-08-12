---
title: "Método System::Nullable::operator!="
linktitle: "operator!="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Nullable::operator!=. Determina si el valor representado por el objeto actual no es igual al valor representado por el objeto Nullable especificado en C++."
type: docs
weight: 1000
url: /es/cpp/system/nullable/operator!=/
---
## Nullable::operator!=(const Nullable\<T1\>\&) const method


Determina si el valor representado por el objeto actual no es igual al valor representado por el objeto [Nullable](../) especificado.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual no es igual al valor representado por el objeto [Nullable](../) especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator!=(const T1\&) const method


Determina si el valor representado por el objeto actual no es igual al valor especificado.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | Una referencia constante al valor con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual no es igual al valor especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator!=(std::nullptr_t) const method


Determina si el valor representado por el objeto actual no es nulo.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### ReturnValue

Verdadero si el valor representado por el objeto actual no es nulo, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
