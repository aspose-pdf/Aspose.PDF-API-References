---
title: System::DateTime::Subtract method
linktitle: Subtract
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTime::Subtract method. Returns an instance of TimeSpan class representing the time interval between the date and time values represented by the current and the specified objects in C++.'
type: docs
weight: 4200
url: /cpp/system/datetime/subtract/
---
## DateTime::Subtract(DateTime) const method


Returns an instance of [TimeSpan](../../timespan/) class representing the time interval between the date and time values represented by the current and the specified objects.

```cpp
TimeSpan System::DateTime::Subtract(DateTime value) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | DateTime | An instance of [DateTime](../) class that marks one end of the interval to be calculated |

### ReturnValue

An instance of [TimeSpan](../../timespan/) class representing the time interval between the date and time values represented by the current object and **value**.

## See Also

* Class [TimeSpan](../../timespan/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::Subtract(TimeSpan) const method


Returns a new instance of the [DateTime](../) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| duration | TimeSpan | A time interval to subtract |

### ReturnValue

A new instance of the [DateTime](../) class representing the date and time value which is the result of subtraction of **duration** from the value represented by the current object.

## See Also

* Class [DateTime](../)
* Class [TimeSpan](../../timespan/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
