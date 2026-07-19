---
title: "Метод System::DateTimeOffset::operator-"
linktitle: "operator-"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::DateTimeOffset::operator-. Возвращает экземпляр класса TimeSpan, представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами в C++."
type: docs
weight: 3500
url: /ru/cpp/system/datetimeoffset/operator-/
---
## DateTimeOffset::operator-(const DateTimeOffset\&) const method


Возвращает экземпляр класса [TimeSpan](../../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const DateTimeOffset\& | Экземпляр класса [DateTime](../../datetime/), обозначающий один конец вычисляемого интервала |

### ReturnValue

Экземпляр класса [TimeSpan](../../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим объектом и **other**.

## См. также

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::operator-(TimeSpan) const method


Возвращает новый экземпляр класса [DateTimeOffset](../), представляющий значение даты и времени, полученное в результате вычитания указанного интервала времени из значения, представленного текущим объектом.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | TimeSpan | Интервал времени для вычитания |

### ReturnValue

Новый экземпляр класса [DateTimeOffset](../), представляющий значение даты и времени, полученное в результате вычитания **value** из значения, представленного текущим объектом.

## См. также

* Class [DateTimeOffset](../)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
