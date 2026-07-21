---
title: "System::DateTimeOffset::operator- método"
linktitle: "operador-"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::DateTimeOffset::operator- método. Devuelve una instancia de la clase TimeSpan que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y los objetos especificados en C++."
type: docs
weight: 3500
url: /es/cpp/system/datetimeoffset/operator-/
---
## DateTimeOffset::operator-(const DateTimeOffset\&) const method


Devuelve una instancia de la clase [TimeSpan](../../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y los objetos especificados.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const DateTimeOffset\& | Una instancia de la clase [DateTime](../../datetime/) que marca uno de los extremos del intervalo a calcular |

### ReturnValue

Una instancia de la clase [TimeSpan](../../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y **other**.

## Ver también

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::operator-(TimeSpan) const method


Devuelve una nueva instancia de la clase [DateTimeOffset](../) que representa el valor de fecha y hora que es el resultado de la sustracción del intervalo de tiempo especificado del valor representado por el objeto actual.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | TimeSpan | Un intervalo de tiempo a restar |

### ReturnValue

Una nueva instancia de la clase [DateTimeOffset](../) que representa el valor de fecha y hora que es el resultado de la sustracción de **value** del valor representado por el objeto actual.

## Ver también

* Class [DateTimeOffset](../)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
