---
title: "System::DateTimeOffset::TryParse метод"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::DateTimeOffset::TryParse метод. Пытается преобразовать указанную строку в объект DateTimeOffset, используя указанный поставщик формата и стиль форматирования в C++."
type: docs
weight: 5700
url: /ru/cpp/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Пытается преобразовать указанную строку в объект [DateTimeOffset](../), используя указанный поставщик формата и стиль форматирования.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |
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
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Пытается преобразовать указанную строку в объект [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |
| result | DateTimeOffset\& | [DateTimeOffset](../) который эквивалентен **input**. |

### ReturnValue

true, если **input** успешно преобразован, иначе - false.

## См. также

* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
