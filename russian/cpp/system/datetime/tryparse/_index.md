---
title: "System::DateTime::TryParse метод"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод TryParse класса System::DateTime в C++."
type: docs
weight: 6900
url: /ru/cpp/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя заданную информацию о формате, зависящем от культуры, и стиль.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строковое представление значения даты и времени для преобразования. |
| provider | const SharedPtr\<IFormatProvider\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий сведения о культуре для форматирования. |
| styles | Globalization::DateTimeStyles | Битовая комбинация значений перечисления, предоставляющая дополнительную информацию о **s**, о стилевых элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |
| result | DateTime\& | Выходной аргумент, который при успешном преобразовании содержит результат конвертации. |

### ReturnValue

True если преобразование успешно, иначе — false.

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, DateTime\&) method


Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../).

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строковое представление значения даты и времени для преобразования. |
| result | DateTime\& | Выходной аргумент, который при успешном преобразовании содержит результат конвертации. |

### ReturnValue

True если преобразование успешно, иначе — false.

## См. также

* Class [String](../../string/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## См. также

* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
