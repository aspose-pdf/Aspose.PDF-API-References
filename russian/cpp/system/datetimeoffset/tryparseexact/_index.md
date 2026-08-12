---
title: "System::DateTimeOffset::TryParseExact метод"
linktitle: "TryParseExact"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::DateTimeOffset::TryParseExact метод. Пытается преобразовать указанную строку в объект DateTimeOffset, используя указанные форматы, поставщик форматов и стиль форматирования в C++."
type: docs
weight: 5800
url: /ru/cpp/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Пытается преобразовать указанную строку в объект [DateTimeOffset](../), используя указанные форматы, поставщик форматов и стиль форматирования.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |
| форматы | const ArrayPtr\<String\>\& | Массивы строк форматов. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик формата. |
| styles | Globalization::DateTimeStyles | Стили форматирования даты и времени. |
| result | DateTimeOffset\& | [DateTimeOffset](../) который эквивалентен **input**. |

### ReturnValue

true, если **input** успешно преобразован, иначе - false.

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Пытается преобразовать указанную строку в объект [DateTimeOffset](../), используя указанный формат, поставщик формата и стиль форматирования.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |
| формат | const String\& | Строка формата. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик формата. |
| styles | Globalization::DateTimeStyles | Стили форматирования даты и времени. |
| result | DateTimeOffset\& | [DateTimeOffset](../) который эквивалентен **input**. |

### ReturnValue

true, если **input** успешно преобразован, иначе - false.

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
