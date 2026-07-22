---
title: "System::DateTime::DateTime konstruktor"
linktitle: "DateTime"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTime::DateTime konstruktor. Skapar en instans som representerar det minsta möjliga datum- och tidsvärdet lika med MinValue i C++."
type: docs
weight: 100
url: /sv/cpp/system/datetime/datetime/
---
## DateTime::DateTime() constructor


Skapar en instans som representerar det minsta möjliga datum- och tidsvärdet som är lika med MinValue.

```cpp
System::DateTime::DateTime()
```

## Se även

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(const DateTime\&) constructor


Kopierar en instans.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dt | const DateTime\& | En instans av klassen [DateTime](../) att kopiera det representerade datum- och tidsvärdet från |

## Se även

* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int) constructor


Skapar en instans som representerar ett datum- och tidsvärde angivet som ett specifikt år, månad och dag.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året som ska representeras av den konstruerade instansen. |
| månad | int | Månaden i **year** som ska representeras av den konstruerade instansen. |
| dag | int | Dagen i **month** som ska representeras av den konstruerade instansen. |

## Se även

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Skapar en instans som representerar ett datum- och tidsvärde angivet som ett specifikt år, månad och dag i den angivna kalendern.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året som ska representeras av den konstruerade instansen. |
| månad | int | Månaden i **year** som ska representeras av den konstruerade instansen. |
| dag | int | Dagen i **month** som ska representeras av den konstruerade instansen. |
| kalender | const SharedPtr\<Globalization::Calendar\>\& | Den kalender som används för att tolka det angivna **year**, **month** och **day**. |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int) constructor


Skapar en instans som representerar ett datum- och tidsvärde angivet som ett specifikt år, månad, dag, timme, minut och sekund.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året som ska representeras av den konstruerade instansen. |
| månad | int | Månaden i **year** som ska representeras av den konstruerade instansen. |
| dag | int | Dagen i **month** som ska representeras av den konstruerade instansen. |
| timme | int | Timmen i **day** som ska representeras av den konstruerade instansen. |
| minut | int | Minuten i **hour** som ska representeras av den konstruerade instansen. |
| sekund | int | Sekunden i **minute** som ska representeras av den konstruerade instansen. |

## Se även

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Skapar en instans som representerar ett datum- och tidsvärde angivet som ett specifikt år, månad, dag, timme, minut och sekund i den angivna kalendern.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året som ska representeras av den konstruerade instansen. |
| månad | int | Månaden i **year** som ska representeras av den konstruerade instansen. |
| dag | int | Dagen i **month** som ska representeras av den konstruerade instansen. |
| timme | int | Timmen i **day** som ska representeras av den konstruerade instansen. |
| minut | int | Minuten i **hour** som ska representeras av den konstruerade instansen. |
| sekund | int | Sekunden i **minute** som ska representeras av den konstruerade instansen. |
| kalender | const SharedPtr\<Globalization::Calendar\>\& | Den kalender som används för att tolka det angivna **year**, **month** och **day**. |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructor


Skapar en instans som representerar ett datum- och tidsvärde angivet som ett specifikt år, månad, dag, timme, minut och sekund.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året som ska representeras av den konstruerade instansen. |
| månad | int | Månaden i **year** som ska representeras av den konstruerade instansen. |
| dag | int | Dagen i **month** som ska representeras av den konstruerade instansen. |
| timme | int | Timmen i **day** som ska representeras av den konstruerade instansen. |
| minut | int | Minuten i **hour** som ska representeras av den konstruerade instansen. |
| sekund | int | Sekunden i **minute** som ska representeras av den konstruerade instansen. |
| typ | DateTimeKind | Värdet som indikerar om de angivna datum- och tidsparametrarna specificerar en lokal tid, UTC-tid eller ingen av dem. |

## Se även

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructor


Skapar en instans som representerar ett datum- och tidsvärde angivet som ett specifikt år, månad, dag, timme, minut, sekund och millisekund i den angivna kalendern.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året som ska representeras av den konstruerade instansen. |
| månad | int | Månaden i **year** som ska representeras av den konstruerade instansen. |
| dag | int | Dagen i **month** som ska representeras av den konstruerade instansen. |
| timme | int | Timmen i **day** som ska representeras av den konstruerade instansen. |
| minut | int | Minuten i **hour** som ska representeras av den konstruerade instansen. |
| sekund | int | Sekunden i **minute** som ska representeras av den konstruerade instansen. |
| millisekund | int | Millisekunden i **second** som ska representeras av den konstruerade instansen. |
| typ | const SharedPtr\<Globalization::Calendar\>\& | Värdet som indikerar om de angivna datum- och tidsparametrarna specificerar en lokal tid, UTC-tid eller ingen av dem. |
| kalender | DateTimeKind | Den kalender som används för att tolka det angivna **year**, **month** och **day**. |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructor


Skapar en instans som representerar ett datum- och tidsvärde angivet som ett specifikt år, månad, dag, timme, minut, sekund och millisekund.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året som ska representeras av den konstruerade instansen. |
| månad | int | Månaden i **year** som ska representeras av den konstruerade instansen. |
| dag | int | Dagen i **month** som ska representeras av den konstruerade instansen. |
| timme | int | Timmen i **day** som ska representeras av den konstruerade instansen. |
| minut | int | Minuten i **hour** som ska representeras av den konstruerade instansen. |
| sekund | int | Sekunden i **minute** som ska representeras av den konstruerade instansen. |
| millisekund | int | Millisekunden i **second** som ska representeras av den konstruerade instansen. |
| typ | DateTimeKind | Värdet som indikerar om de angivna datum- och tidsparametrarna specificerar en lokal tid, UTC-tid eller ingen av dem. |

## Se även

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind, bool) constructor


Skapa en instans som representerar ett datum- och tidsvärde angivet som ett antal ticks. FÖR INTERNT ANVÄNDNING.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tick | int64_t | Antalet 100‑ns intervall som har passerat sedan 1 januari 0001 00:00:00.000 i den georgiska kalendern. |
| typ | DateTimeKind | Värdet som indikerar om parametern **ticks** specificerar en lokal tid, UTC-tid eller ingen av dem. |
| is_ambiguous_local_dst | bool | Sant om det angivna datumet och tiden är tvetydiga och kan mappas till många UTC-tider. |

## Se även

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind) constructor


Skapa en instans som representerar ett datum- och tidsvärde angivet som ett antal ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tick | int64_t | Antalet 100‑ns intervall som har passerat sedan 1 januari 0001 00:00:00.000 i den georgiska kalendern. |
| typ | DateTimeKind | Värdet som indikerar om parametern **ticks** specificerar en lokal tid, UTC-tid eller ingen av dem. |

## Se även

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
