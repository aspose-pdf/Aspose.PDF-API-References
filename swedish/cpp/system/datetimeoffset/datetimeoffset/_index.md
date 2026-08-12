---
title: "System::DateTimeOffset::DateTimeOffset konstruktor"
linktitle: "DateTimeOffset"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTimeOffset::DateTimeOffset konstruktor. Standardkonstruktor i C++."
type: docs
weight: 100
url: /sv/cpp/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() constructor


Standardkonstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset()=default
```

## Se även

* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(DateTime) constructor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | DateTime | Datum och tid. |

## Se även

* Class [DateTime](../../datetime/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) constructor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | DateTime | Datum och tid. |
| förskjutning | TimeSpan | Tidsförskjutning från UTC. |

## Se även

* Class [DateTime](../../datetime/)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) constructor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | År. |
| månad | int | Månad (1 till 12). |
| dag | int | Dag (1 till antalet dagar i månaden). |
| timme | int | Timme (0 till 23). |
| minut | int | Minut (0 till 59). |
| sekund | int | Sekund (0 till 59). |
| millisekund | int | Millisekund (0 till 999). |
| kalender | const SharedPtr\<Globalization::Calendar\>\& | Kalender som används för att tolka år, månad och dag. |
| förskjutning | TimeSpan | Tidsförskjutning från UTC. |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) constructor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | År (1 till 9999). |
| månad | int | Månad (1 till 12). |
| dag | int | Dag (1 till antalet dagar i månaden). |
| timme | int | Timme (0 till 23). |
| minut | int | Minut (0 till 59). |
| sekund | int | Sekund (0 till 59). |
| millisekund | int | Millisekund (0 till 999). |
| förskjutning | TimeSpan | Tidsförskjutning från UTC. |

## Se även

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) constructor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | År (1 till 9999). |
| månad | int | Månad (1 till 12). |
| dag | int | Dag (1 till antalet dagar i månaden). |
| timme | int | Timme (0 till 23). |
| minut | int | Minut (0 till 59). |
| sekund | int | Sekund (0 till 59). |
| förskjutning | TimeSpan | Tidsförskjutning från UTC. |

## Se även

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) constructor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tick | int64_t | Antal tickar. |
| förskjutning | TimeSpan | Tidsförskjutning från UTC. |

## Se även

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
