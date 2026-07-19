---
title: "Метод System::TimeSpan::ParseExact"
linktitle: "ParseExact"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод ParseExact класса System::TimeSpan в C++."
type: docs
weight: 4300
url: /ru/cpp/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method


Преобразует строку в эквивалентный объект [TimeSpan](../), используя указанные форматы, поставщик форматов и стили.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) строк форматов. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| styles | Globalization::TimeSpanStyles | Определяет элементы, которые могут присутствовать во входной строке. |

### ReturnValue

Временной интервал, соответствующий строке.

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method


Преобразует строку в эквивалентный объект [TimeSpan](../), используя указанный формат, поставщик форматов и стили.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| формат | const String\& | Стандартная или пользовательская строка формата. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| styles | Globalization::TimeSpanStyles | Определяет элементы, которые могут присутствовать во входной строке. |

### ReturnValue

Временной интервал, соответствующий строке.

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## См. также

* Class [TimeSpan](../)
* Class [String](../../string/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
