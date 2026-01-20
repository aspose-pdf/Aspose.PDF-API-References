---
title: System::DateTimeOffset::TryParseExact method
linktitle: TryParseExact
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTimeOffset::TryParseExact method. Tries to converts the specified string to DateTimeOffset object using the specified formats, format provider and formatting style in C++.'
type: docs
weight: 5800
url: /cpp/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Tries to converts the specified string to [DateTimeOffset](../) object using the specified formats, format provider and formatting style.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |
| formats | const ArrayPtr\<String\>\& | Arrays of format strings. |
| provider | const SharedPtr\<IFormatProvider\>\& | Format provider. |
| styles | Globalization::DateTimeStyles | Date and time formatting styles. |
| result | DateTimeOffset\& | [DateTimeOffset](../) that is equivalent to the **input**. |

### ReturnValue

true if the **input** converted successfully, otherwise - false.

## See Also

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


Tries to converts the specified string to [DateTimeOffset](../) object using the specified format, format provider and formatting style.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |
| format | const String\& | Format string. |
| provider | const SharedPtr\<IFormatProvider\>\& | Format provider. |
| styles | Globalization::DateTimeStyles | Date and time formatting styles. |
| result | DateTimeOffset\& | [DateTimeOffset](../) that is equivalent to the **input**. |

### ReturnValue

true if the **input** converted successfully, otherwise - false.

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
