---
title: System::DateTime::operator- method
linktitle: operator-
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTime::operator- method. Returns an instance of TimeSpan class that represents the time interval between the date and time values represented by the current and the specified objects in C++.'
type: docs
weight: 3400
url: /cpp/system/datetime/operator-/
---
## DateTime::operator-(DateTime) const method


Returns an instance of [TimeSpan](../../timespan/) class that represents the time interval between the date and time values represented by the current and the specified objects.

```cpp
TimeSpan System::DateTime::operator-(DateTime value) const
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
## DateTime::operator-(TimeSpan) const method


Returns a new instance of the [DateTime](../) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | TimeSpan | A time interval to subtract |

### ReturnValue

A new instance of the [DateTime](../) class representing the date and time value which is the result of subtraction of **value** from the value represented by the current object.

## See Also

* Class [DateTime](../)
* Class [TimeSpan](../../timespan/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
