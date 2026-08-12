---
title: "System::DateTimeOffset::Parse метод"
linktitle: "Разобрать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::DateTimeOffset::Parse метод. Преобразует указанную строку в эквивалент DateTimeOffset в C++."
type: docs
weight: 5500
url: /ru/cpp/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) method


Преобразует указанную строку в эквивалент [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## См. также

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Преобразует указанную строку в объект [DateTimeOffset](../), используя указанный поставщик формата и стиль форматирования.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик формата. |
| styles | Globalization::DateTimeStyles | Стили форматирования даты и времени. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## См. также

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
