---
title: System::DateTimeOffset::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTimeOffset::TryParse method. Tries to converts the specified string to DateTimeOffset object using the specified format provider and formatting style in C++.'
type: docs
weight: 5700
url: /cpp/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Tries to converts the specified string to [DateTimeOffset](../) object using the specified format provider and formatting style.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |
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
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Tries to converts the specified string to [DateTimeOffset](../) object.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../string/) to convert. |
| result | DateTimeOffset\& | [DateTimeOffset](../) that is equivalent to the **input**. |

### ReturnValue

true if the **input** converted successfully, otherwise - false.

## See Also

* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
