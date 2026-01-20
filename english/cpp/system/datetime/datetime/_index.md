---
title: System::DateTime::DateTime constructor
linktitle: DateTime
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTime::DateTime constructor. Constructs an instance that represents the smallest possible date and time value equal to MinValue in C++.'
type: docs
weight: 100
url: /cpp/system/datetime/datetime/
---
## DateTime::DateTime() constructor


Constructs an instance that represents the smallest possible date and time value equal to MinValue.

```cpp
System::DateTime::DateTime()
```

## See Also

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(const DateTime\&) constructor


Copy-constructs an instance.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


| Parameter | Type | Description |
| --- | --- | --- |
| dt | const DateTime\& | An instance of [DateTime](../) class to copy the represented date and time value from |

## See Also

* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int) constructor


Constructs an instance that represents a date and time value specified as a particular year, month and day.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |

## See Also

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Constructs an instance that represents a date and time value specified as a particular year, month and day in the specified calendar.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| calendar | const SharedPtr\<Globalization::Calendar\>\& | The calendar used to interpret the specified **year**, **month** and **day**. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |

## See Also

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second in the specified calendar.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| calendar | const SharedPtr\<Globalization::Calendar\>\& | The calendar used to interpret the specified **year**, **month** and **day**. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| kind | DateTimeKind | The value that indicates if the provided date and time parameters specify a local time, UTC time or neither. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond in the specified calendar.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| millisecond | int | The millisecond of the **second** to be represented by the instance being constructed. |
| kind | const SharedPtr\<Globalization::Calendar\>\& | The value that indicates if the provided date and time parameters specify a local time, UTC time or neither. |
| calendar | DateTimeKind | The calendar used to interpret the specified **year**, **month** and **day**. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| millisecond | int | The millisecond of the **second** to be represented by the instance being constructed. |
| kind | DateTimeKind | The value that indicates if the provided date and time parameters specify a local time, UTC time or neither. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind, bool) constructor


Construct an instance that represents a date and time value specified as a number of ticks. FOR INTERNAL USE.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ticks | int64_t | The number of 100-ns intervals that have passed since January the 1st, 0001 00:00:00.000 in Georgian calendar. |
| kind | DateTimeKind | The value that indicates if **ticks** parameter specifies a local time, UTC time or neither. |
| is_ambiguous_local_dst | bool | True if specified date and time is ambiguous and can be mapped to many UTC times. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind) constructor


Construct an instance that represents a date and time value specified as a number of ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ticks | int64_t | The number of 100-ns intervals that have passed since January the 1st, 0001 00:00:00.000 in Georgian calendar. |
| kind | DateTimeKind | The value that indicates if **ticks** parameter specifies a local time, UTC time or neither. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
