---
title: "Método System::operator<="
linktitle: "operator<="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::operator<=. Determina si el valor especificado es menor o igual al valor representado por el objeto Nullable especificado aplicando operator<=() a estos valores en C++."
type: docs
weight: 32700
url: /es/cpp/system/operator_=/
---
## System::operator<=(const T1\&, const Nullable\<T2\>\&) method


Determina si el valor especificado es menor o igual al valor representado por el objeto [Nullable](../nullable/) especificado aplicando [operator<=()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del primer valor comparado |
| T2 | El tipo subyacente del objeto [Nullable](../nullable/) que representa el segundo valor comparado |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alguno | const T1\& | Una referencia constante al valor que se usará como el primer operando |
| other | const Nullable\<T2\>\& | Una referencia constante al objeto [Nullable](../nullable/) cuyo valor representado se usará como el segundo comparando |

### ReturnValue

Verdadero si el primer comparando es menor o igual al segundo comparando, de lo contrario - falso

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## Ver también

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) method


Siempre devuelve false.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, DateTime) method




```cpp
bool System::operator<=(std::nullptr_t, DateTime)
```

## Ver también

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator<=(std::nullptr_t, TimeSpan)
```

## Ver también

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
title: System::operator>= método
linktitle: operator>=
second_title: Referencia de API de Aspose.PDF para C++
description: 'System::operator>= método. Determina si el valor especificado es mayor o igual al valor representado por el objeto Nullable especificado al aplicar operator>=() a estos valores en C++.'
type: docs
peso: 35400
url: /cpp/system/operator_=/
---
## System::operator>=(const T1\&, const Nullable\<T2\>\&) method


Determina si el valor especificado es mayor o igual al valor representado por el objeto [Nullable](../nullable/) especificado al aplicar [operator>=()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del primer valor comparado |
| T2 | El tipo subyacente del objeto [Nullable](../nullable/) que representa el segundo valor comparado |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alguno | const T1\& | Una referencia constante al valor que se usará como el primer operando |
| other | const Nullable\<T2\>\& | Una referencia constante al objeto [Nullable](../nullable/) cuyo valor representado se usará como el segundo comparando |

### ReturnValue

Verdadero si el primer comparando es mayor o igual que el segundo comparando, de lo contrario - falso

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## Ver también

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) method


Siempre devuelve false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, DateTime) method




```cpp
bool System::operator>=(std::nullptr_t, DateTime)
```

## Ver también

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator>=(std::nullptr_t, TimeSpan)
```

## Ver también

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
