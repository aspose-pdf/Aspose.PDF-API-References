---
title: System::DateTimeOffset::DateTimeOffset constructor
linktitle: DateTimeOffset
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTimeOffset::DateTimeOffset constructor. Default constructor in C++.'
type: docs
weight: 100
url: /cpp/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() constructor


Default constructor.

```cpp
System::DateTimeOffset::DateTimeOffset()=default
```

## See Also

* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(DateTime) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```


| Parameter | Type | Description |
| --- | --- | --- |
| date_time | DateTime | Date and time. |

## See Also

* Class [DateTime](../../datetime/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```


| Parameter | Type | Description |
| --- | --- | --- |
| date_time | DateTime | Date and time. |
| offset | TimeSpan | Time offset from UTC. |

## See Also

* Class [DateTime](../../datetime/)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | Year. |
| month | int | Month (1 through 12). |
| day | int | Day (1 through the number of days in month). |
| hour | int | Hour (0 through 23). |
| minute | int | Minute (0 through 59). |
| second | int | Second (0 through 59). |
| millisecond | int | Millisecond (0 through 999). |
| calendar | const SharedPtr\<Globalization::Calendar\>\& | Calendar used to interpret year, month, and day. |
| offset | TimeSpan | Time offset from UTC. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | Year (1 through 9999). |
| month | int | Month (1 through 12). |
| day | int | Day (1 through the number of days in month). |
| hour | int | Hour (0 through 23). |
| minute | int | Minute (0 through 59). |
| second | int | Second (0 through 59). |
| millisecond | int | Millisecond (0 through 999). |
| offset | TimeSpan | Time offset from UTC. |

## See Also

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```


| Parameter | Type | Description |
| --- | --- | --- |
| year | int | Year (1 through 9999). |
| month | int | Month (1 through 12). |
| day | int | Day (1 through the number of days in month). |
| hour | int | Hour (0 through 23). |
| minute | int | Minute (0 through 59). |
| second | int | Second (0 through 59). |
| offset | TimeSpan | Time offset from UTC. |

## See Also

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ticks | int64_t | Number of ticks. |
| offset | TimeSpan | Time offset from UTC. |

## See Also

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
