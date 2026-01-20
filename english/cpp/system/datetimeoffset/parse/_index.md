---
title: System::DateTimeOffset::Parse method
linktitle: Parse
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTimeOffset::Parse method. Converts the specified string to DateTimeOffset equivalent in C++.'
type: docs
weight: 5500
url: /cpp/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) method


Converts the specified string to [DateTimeOffset](../) equivalent.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## See Also

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Converts the specified string to [DateTimeOffset](../) object using the specified format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |
| provider | const SharedPtr\<IFormatProvider\>\& | Format provider. |
| styles | Globalization::DateTimeStyles | Date and time formatting styles. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## See Also

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
