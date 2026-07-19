---
title: "System::DateTimeOffset::ParseExact метод"
linktitle: "ParseExact"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::DateTimeOffset::ParseExact метод. Преобразует указанную строку в объект DateTimeOffset, используя указанные форматы, поставщик формата и стиль форматирования в C++."
type: docs
weight: 5600
url: /ru/cpp/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Преобразует указанную строку в объект [DateTimeOffset](../), используя указанные форматы, поставщик формата и стиль форматирования.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) строк форматов. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Поставщик формата. |
| styles | Globalization::DateTimeStyles | Стили форматирования даты и времени. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## См. также

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Преобразует указанную строку в объект [DateTimeOffset](../), используя указанный формат, поставщик формата и стиль форматирования.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | [String](../../string/) для преобразования. |
| формат | const String\& | Строка формата. |
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
