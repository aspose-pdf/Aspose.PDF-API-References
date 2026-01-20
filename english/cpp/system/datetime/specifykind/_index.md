---
title: System::DateTime::SpecifyKind method
linktitle: SpecifyKind
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTime::SpecifyKind method. Constructs a new DateTime object that represents the same number of ticks as the specified DateTime object and represents local time, UTC time or neither as specified by the argument kind in C++.'
type: docs
weight: 6800
url: /cpp/system/datetime/specifykind/
---
## DateTime::SpecifyKind method


Constructs a new [DateTime](../) object that represents the same number of ticks as the specified [DateTime](../) object and represents local time, UTC time or neither as specified by the argument **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | DateTime | The [DateTime](../) object to copy the number of ticks from |
| kind | DateTimeKind | Specifies if the new object should represent local time, UTC time or neither. |

### ReturnValue

A new [DateTime](../) object that represents the same number of ticks as **value** and [DateTimeKind](../../datetimekind/) value specified by **kind**.

## See Also

* Class [DateTime](../)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
