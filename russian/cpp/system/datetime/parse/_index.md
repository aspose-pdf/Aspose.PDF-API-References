---
title: "Метод System::DateTime::Parse"
linktitle: "Разобрать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::DateTime::Parse. Преобразует указанное строковое представление значения даты и времени в эквивалентный объект DateTime в C++."
type: docs
weight: 6600
url: /ru/cpp/system/datetime/parse/
---
## DateTime::Parse(const String\&) method


Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../).

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строковое представление значения даты и времени для преобразования. |

### ReturnValue

Новый экземпляр класса [DateTime](../), представляющий значение даты и времени, эквивалентное тому, которое представлено указанной строкой.

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
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
## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
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
## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя сведения о формате, специфичном для культуры.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строковое представление значения даты и времени для преобразования. |
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
## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## См. также

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
