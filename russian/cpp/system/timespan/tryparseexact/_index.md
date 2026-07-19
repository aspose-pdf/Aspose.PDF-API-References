---
title: "System::TimeSpan::TryParseExact метод"
linktitle: "TryParseExact"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод TryParseExact класса System::TimeSpan в C++."
type: docs
weight: 4500
url: /ru/cpp/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Преобразует строку в эквивалентный объект [TimeSpan](../), используя указанные форматы, поставщик форматов и стили, и возвращает результат преобразования.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) строк форматов. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| styles | Globalization::TimeSpanStyles | Определяет элементы, которые могут присутствовать во входной строке. |
| result | TimeSpan\& | Временной интервал, соответствующий строке. |

### ReturnValue

True, если строка была успешно преобразована; иначе false.

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Преобразует строку в эквивалентный объект [TimeSpan](../), используя указанные форматы и поставщик форматов, и возвращает результат преобразования.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) строк форматов. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| result | TimeSpan\& | Временной интервал, соответствующий строке. |

### ReturnValue

True, если строка была успешно преобразована; иначе false.

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Преобразует строку в эквивалентный объект [TimeSpan](../), используя указанный формат, поставщик форматов и стили, и возвращает результат преобразования.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| формат | const String\& | Стандартная или пользовательская строка формата. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| styles | Globalization::TimeSpanStyles | Определяет элементы, которые могут присутствовать во входной строке. |
| result | TimeSpan\& | Временной интервал, соответствующий строке. |

### ReturnValue

True, если строка была успешно преобразована; иначе false.

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Преобразует строку в эквивалентный объект [TimeSpan](../), используя указанный формат и поставщик форматов, и возвращает результат преобразования.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| формат | const String\& | Стандартная или пользовательская строка формата. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| result | TimeSpan\& | Временной интервал, соответствующий строке. |

### ReturnValue

True, если строка была успешно преобразована; иначе false.

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## См. также

* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
