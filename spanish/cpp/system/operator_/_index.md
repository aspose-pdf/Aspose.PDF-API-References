---
title: "Método System::operator*"
linktitle: "operador*"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::operator*. Devuelve una nueva instancia de la clase Decimal que representa un valor que es el resultado de la multiplicación del valor especificado y el valor representado por el objeto Decimal especificado en C++."
type: docs
weight: 28200
url: /es/cpp/system/operator_/
---
## System::operator* method


Devuelve una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es el resultado de la multiplicación del valor especificado y el valor representado por el objeto [Decimal](../decimal/) especificado.

```cpp
template<typename T,typename _> Decimal System::operator*(const T &x, const Decimal &d)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const T\& | El primer multiplicador |
| d | const Decimal\& | El objeto [Decimal](../decimal/) que representa el segundo multiplicador |

### ReturnValue

Una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es el resultado de la multiplicación de **x** y el valor representado por **d**.

## Ver también

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
title: método System::operator<
linktitle: operator<
second_title: Referencia de API de Aspose.PDF para C++
description: 'Método System::operator<. Determina si el valor especificado es menor que el valor representado por el objeto Nullable especificado al aplicar operator<() a estos valores en C++.'
type: docs
weight: 29400
url: /cpp/system/operator_/
---
## System::operator<(const T1\&, const Nullable\<T2\>\&) method


Determina si el valor especificado es menor que el valor representado por el objeto [Nullable](../nullable/) especificado al aplicar [operator<()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
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

Verdadero si el primer comparando es menor que el segundo comparando, de lo contrario - falso

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## Ver también

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, const Nullable\<T\>\&) method


Siempre devuelve false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, DateTime) method




```cpp
bool System::operator<(std::nullptr_t, DateTime)
```

## Ver también

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator<(std::nullptr_t, TimeSpan)
```

## Ver también

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
title: método System::operator>
linktitle: operator>
second_title: Referencia de API de Aspose.PDF para C++
description: 'Método System::operator>. Determina si el valor especificado es mayor que el valor representado por el objeto Nullable especificado al aplicar operator>() a estos valores en C++.'
type: docs
weight: 34900
url: /cpp/system/operator_/
---
## System::operator>(const T1\&, const Nullable\<T2\>\&) method


Determina si el valor especificado es mayor que el valor representado por el objeto [Nullable](../nullable/) especificado al aplicar [operator>()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
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

Verdadero si el primer comparando es mayor que el segundo comparando, de lo contrario - falso

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## Ver también

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, const Nullable\<T\>\&) method


Siempre devuelve false.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, DateTime) method




```cpp
bool System::operator>(std::nullptr_t, DateTime)
```

## Ver también

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator>(std::nullptr_t, TimeSpan)
```

## Ver también

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
