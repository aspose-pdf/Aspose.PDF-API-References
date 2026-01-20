---
title: System::DateTimeOffset::ParseExact method
linktitle: ParseExact
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTimeOffset::ParseExact method. Converts the specified string to DateTimeOffset object using the specified formats, format provider and formatting style in C++.'
type: docs
weight: 5600
url: /cpp/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Converts the specified string to [DateTimeOffset](../) object using the specified formats, format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) of format strings. |
| provider | const SharedPtr\<IFormatProvider\>\& | Format provider. |
| styles | Globalization::DateTimeStyles | Date and time formatting styles. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## See Also

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


Converts the specified string to [DateTimeOffset](../) object using the specified format, format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |
| format | const String\& | Format string. |
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
