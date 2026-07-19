---
title: "Метод System::DateTime::ParseExact"
linktitle: "ParseExact"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод ParseExact класса System::DateTime в C++."
type: docs
weight: 6700
url: /ru/cpp/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя указанные форматы, сведения о культуре и стиль. Формат строкового представления должен точно соответствовать одному или нескольким из указанных форматов. Выбрасывает исключение, если преобразование не удалось.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строковое представление значения даты и времени для преобразования. |
| форматы | const ArrayPtr\<String\>\& | Массив строковых форматов. |
| provider | const SharedPtr\<IFormatProvider\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий сведения о культуре для форматирования. |
| styles | Globalization::DateTimeStyles | Битовая комбинация значений перечисления, предоставляющая дополнительную информацию о **s**, о стилевых элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |

### ReturnValue

Новый экземпляр класса [DateTime](../), представляющий значение даты и времени, эквивалентное тому, которое представлено указанной строкой.

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя указанный формат и сведения о культуре. Формат строкового представления должен точно соответствовать указанному формату. Выбрасывает исключение, если преобразование не удалось.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строковое представление значения даты и времени для преобразования. |
| формат | const String\& | Строковый формат. |
| provider | const SharedPtr\<IFormatProvider\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий сведения о культуре для форматирования. |
| styles | Globalization::DateTimeStyles | Битовая комбинация значений перечисления, предоставляющая дополнительную информацию о **s**, о стилевых элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |

### ReturnValue

Новый экземпляр класса [DateTime](../), представляющий значение даты и времени, эквивалентное тому, которое представлено указанной строкой.

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
