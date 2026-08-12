---
title: "Конструктор System::DateTime::DateTime"
linktitle: "DateTime"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::DateTime::DateTime. Создаёт экземпляр, представляющий наименьшее возможное значение даты и времени, равное MinValue, в C++."
type: docs
weight: 100
url: /ru/cpp/system/datetime/datetime/
---
## DateTime::DateTime() constructor


Создаёт экземпляр, представляющий наименьшее возможное значение даты и времени, равное MinValue.

```cpp
System::DateTime::DateTime()
```

## См. также

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(const DateTime\&) constructor


Создаёт копию экземпляра.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dt | const DateTime\& | Экземпляр класса [DateTime](../), из которого копировать представленное значение даты и времени |

## См. также

* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем и днём.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| год | int | Год, который будет представлен создаваемым экземпляром. |
| месяц | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| день | int | День **month**, который будет представлен создаваемым экземпляром. |

## См. также

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем и днём в указанном календаре.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| год | int | Год, который будет представлен создаваемым экземпляром. |
| месяц | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| день | int | День **month**, который будет представлен создаваемым экземпляром. |
| календарь | const SharedPtr\<Globalization::Calendar\>\& | Календарь, используемый для интерпретации указанных **year**, **month** и **day**. |

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| год | int | Год, который будет представлен создаваемым экземпляром. |
| месяц | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| день | int | День **month**, который будет представлен создаваемым экземпляром. |
| час | int | Час **day**, который будет представлен создаваемым экземпляром. |
| минута | int | Минута **hour**, которая будет представлена создаваемым экземпляром. |
| секунда | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |

## См. также

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой в указанном календаре.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| год | int | Год, который будет представлен создаваемым экземпляром. |
| месяц | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| день | int | День **month**, который будет представлен создаваемым экземпляром. |
| час | int | Час **day**, который будет представлен создаваемым экземпляром. |
| минута | int | Минута **hour**, которая будет представлена создаваемым экземпляром. |
| секунда | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| календарь | const SharedPtr\<Globalization::Calendar\>\& | Календарь, используемый для интерпретации указанных **year**, **month** и **day**. |

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| год | int | Год, который будет представлен создаваемым экземпляром. |
| месяц | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| день | int | День **month**, который будет представлен создаваемым экземпляром. |
| час | int | Час **day**, который будет представлен создаваемым экземпляром. |
| минута | int | Минута **hour**, которая будет представлена создаваемым экземпляром. |
| секунда | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| вид | DateTimeKind | Значение, указывающее, задают ли предоставленные параметры даты и времени локальное время, время UTC или ни то, ни другое. |

## См. также

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой, секундой и миллисекундой в указанном календаре.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| год | int | Год, который будет представлен создаваемым экземпляром. |
| месяц | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| день | int | День **month**, который будет представлен создаваемым экземпляром. |
| час | int | Час **day**, который будет представлен создаваемым экземпляром. |
| минута | int | Минута **hour**, которая будет представлена создаваемым экземпляром. |
| секунда | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| миллисекунда | int | Миллисекунда **second**, которая будет представлена создаваемым экземпляром. |
| вид | const SharedPtr\<Globalization::Calendar\>\& | Значение, указывающее, задают ли предоставленные параметры даты и времени локальное время, время UTC или ни то, ни другое. |
| календарь | DateTimeKind | Календарь, используемый для интерпретации указанных **year**, **month** и **day**. |

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой, секундой и миллисекундой.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| год | int | Год, который будет представлен создаваемым экземпляром. |
| месяц | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| день | int | День **month**, который будет представлен создаваемым экземпляром. |
| час | int | Час **day**, который будет представлен создаваемым экземпляром. |
| минута | int | Минута **hour**, которая будет представлена создаваемым экземпляром. |
| секунда | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| миллисекунда | int | Миллисекунда **second**, которая будет представлена создаваемым экземпляром. |
| вид | DateTimeKind | Значение, указывающее, задают ли предоставленные параметры даты и времени локальное время, время UTC или ни то, ни другое. |

## См. также

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind, bool) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное числом тиков. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| тиков | int64_t | Количество интервалов по 100 нс, прошедших с 1 января 0001 г. 00:00:00.000 по грузинскому календарю. |
| вид | DateTimeKind | Значение, указывающее, задаёт ли параметр **ticks** локальное время, время UTC или ни то, ни другое. |
| is_ambiguous_local_dst | bool | True, если указанная дата и время неоднозначны и могут быть сопоставлены с множеством UTC‑времен. |

## См. также

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind) constructor


Создаёт экземпляр, представляющий значение даты и времени, заданное числом тиков.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| тиков | int64_t | Количество интервалов по 100 нс, прошедших с 1 января 0001 г. 00:00:00.000 по грузинскому календарю. |
| вид | DateTimeKind | Значение, указывающее, задаёт ли параметр **ticks** локальное время, время UTC или ни то, ни другое. |

## См. также

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
