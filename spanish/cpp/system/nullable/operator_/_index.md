---
title: "Método System::Nullable::operator<"
linktitle: "operator<"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Nullable::operator< método. Determina si el valor representado por el objeto actual es menor que el valor representado por el objeto Nullable especificado al aplicar operator<() a estos valores en C++."
type: docs
weight: 1600
url: /es/cpp/system/nullable/operator_/
---
## Nullable::operator<(const Nullable\<T1\>\&) const method


Determina si el valor representado por el objeto actual es menor que el valor representado por el objeto [Nullable](../) especificado al aplicar [operator<()](./) a estos valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es menor que el valor representado por el objeto [Nullable](../) especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<(const T1\&) const method


Determina si el valor representado por el objeto actual es menor que el valor especificado al aplicar [operator<()](./) a estos valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | Una referencia constante al valor con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es menor que el valor especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<(std::nullptr_t) const method


Siempre devuelve false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
título: System::Nullable::operator> método
linktitle: operator>
second_title: Referencia de API de Aspose.PDF para C++
descripción: 'System::Nullable::operator> método. Determina si el valor representado por el objeto actual es mayor que el valor representado por el objeto Nullable especificado al aplicar operator>() a estos valores en C++.'
type: docs
peso: 2000
url: /cpp/system/nullable/operator_/
---
## Nullable::operator>(const Nullable\<T1\>\&) const method


Determina si el valor representado por el objeto actual es mayor que el valor representado por el objeto [Nullable](../) especificado al aplicar [operator>()](./) a estos valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es mayor que el valor representado por el objeto [Nullable](../) especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>(const T1\&) const method


Determina si el valor representado por el objeto actual es mayor que el valor especificado al aplicar [operator>()](./) a estos valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | Una referencia constante al valor con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es mayor que el valor especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>(std::nullptr_t) const method


Siempre devuelve false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
