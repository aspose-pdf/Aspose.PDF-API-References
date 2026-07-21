---
title: "System::DateTime::DateTime constructor"
linktitle: "DateTime"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::DateTime::DateTime constructor. Construye una instancia que representa el valor de fecha y hora más pequeño posible, igual a MinValue en C++."
type: docs
weight: 100
url: /es/cpp/system/datetime/datetime/
---
## DateTime::DateTime() constructor


Construye una instancia que representa el valor de fecha y hora más pequeño posible, igual a MinValue.

```cpp
System::DateTime::DateTime()
```

## Ver también

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(const DateTime\&) constructor


Construye una instancia mediante copia.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dt | const DateTime\& | Una instancia de la clase [DateTime](../) desde la cual copiar el valor de fecha y hora representado |

## Ver también

* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día concretos.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| día | int | El día del **month** que será representado por la instancia que se está construyendo. |

## Ver también

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día concretos en el calendario especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| día | int | El día del **month** que será representado por la instancia que se está construyendo. |
| calendario | const SharedPtr\<Globalization::Calendar\>\& | El calendario usado para interpretar el **year**, **month** y **day** especificados. |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo concretos.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| día | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hora | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minuto | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| segundo | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |

## Ver también

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo concretos en el calendario especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| día | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hora | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minuto | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| segundo | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| calendario | const SharedPtr\<Globalization::Calendar\>\& | El calendario usado para interpretar el **year**, **month** y **day** especificados. |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo concretos.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| día | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hora | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minuto | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| segundo | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| tipo | DateTimeKind | El valor que indica si los parámetros de fecha y hora proporcionados especifican una hora local, hora UTC o ninguna. |

## Ver también

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo concretos en el calendario especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| día | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hora | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minuto | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| segundo | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| milisegundo | int | El milisegundo del **second** que será representado por la instancia que se está construyendo. |
| tipo | const SharedPtr\<Globalization::Calendar\>\& | El valor que indica si los parámetros de fecha y hora proporcionados especifican una hora local, hora UTC o ninguna. |
| calendario | DateTimeKind | El calendario usado para interpretar el **year**, **month** y **day** especificados. |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo concretos.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| día | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hora | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minuto | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| segundo | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| milisegundo | int | El milisegundo del **second** que será representado por la instancia que se está construyendo. |
| tipo | DateTimeKind | El valor que indica si los parámetros de fecha y hora proporcionados especifican una hora local, hora UTC o ninguna. |

## Ver también

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind, bool) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks. PARA USO INTERNO.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ticks | int64_t | El número de intervalos de 100-ns que han pasado desde el 1 de enero de 0001 00:00:00.000 en el calendario georgiano. |
| tipo | DateTimeKind | El valor que indica si el parámetro **ticks** especifica una hora local, hora UTC o ninguna. |
| is_ambiguous_local_dst | bool | Verdadero si la fecha y hora especificadas son ambiguas y pueden mapearse a muchas horas UTC. |

## Ver también

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind) constructor


Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ticks | int64_t | El número de intervalos de 100-ns que han pasado desde el 1 de enero de 0001 00:00:00.000 en el calendario georgiano. |
| tipo | DateTimeKind | El valor que indica si el parámetro **ticks** especifica una hora local, hora UTC o ninguna. |

## Ver también

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
