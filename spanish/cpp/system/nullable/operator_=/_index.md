---
title: "Método System::Nullable::operator<="
linktitle: "operator<="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Nullable::operator<=. Determina si el valor representado por el objeto actual es menor o igual al valor representado por el objeto Nullable especificado aplicando operator<=() a estos valores en C++."
type: docs
weight: 1700
url: /es/cpp/system/nullable/operator_=/
---
## Nullable::operator<=(const Nullable\<T1\>\&) const method


Determina si el valor representado por el objeto actual es menor o igual al valor representado por el objeto [Nullable](../) especificado aplicando [operator<=()](./) a estos valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es menor o igual al valor representado por el objeto [Nullable](../) especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(const T1\&) const method


Determina si el valor representado por el objeto actual es menor o igual al valor especificado aplicando [operator<=()](./) a estos valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | Una referencia constante al valor con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es menor o igual al valor especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(std::nullptr_t) const method


Siempre devuelve false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
título: System::Nullable::operator>= método
linktitle: operator>=
second_title: Referencia de API de Aspose.PDF para C++
descripción: 'System::Nullable::operator>= método. Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto Nullable especificado aplicando operator>=() a estos valores en C++.'
type: docs
peso: 2100
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator>=(const Nullable\<T1\>\&) const method


Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto [Nullable](../) especificado aplicando [operator>=()](./) a estos valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### ReturnValue

Verdadero si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto [Nullable](../) especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(const T1\&) const method


Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto especificado aplicando [operator>=()](./) a estos valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del valor con el que comparar el valor representado por el objeto actual |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | Una referencia constante a un objeto con el que comparar el objeto actual |

### ReturnValue

Verdadero si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto especificado, de lo contrario - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(std::nullptr_t) const method


Siempre devuelve false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### ReturnValue

Siempre - falso

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
título: System::Nullable::operator|= método
título del enlace: operator|=
second_title: Referencia de API de Aspose.PDF para C++
descripción: 'System::Nullable::operator|= método. Aplica operator|=() al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho en C++.'
type: docs
peso: 2200
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator|= method


Aplica [operator|=()](./) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El parámetro de plantilla para que SFINAE funcione. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | bool | Un valor booleano que se usa como valor del lado derecho del [operator | =()](./) aplicado al valor representado por el objeto actual. |

### ReturnValue

Una referencia al propio objeto.

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
