---
title: "System::DateTime::SpecifyKind metod"
linktitle: "SpecifyKind"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTime::SpecifyKind metod. Skapar ett nytt DateTime-objekt som representerar samma antal ticks som det angivna DateTime-objektet och representerar lokal tid, UTC-tid eller ingen av dem enligt argumentet kind i C++."
type: docs
weight: 6800
url: /sv/cpp/system/datetime/specifykind/
---
## DateTime::SpecifyKind method


Skapar ett nytt [DateTime](../)-objekt som representerar samma antal ticks som det angivna [DateTime](../)-objektet och representerar lokal tid, UTC-tid eller ingen av dem enligt argumentet **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | DateTime | Det [DateTime](../)-objektet att kopiera antalet ticks från |
| typ | DateTimeKind | Anger om det nya objektet ska representera lokal tid, UTC-tid eller ingen av dem. |

### ReturnValue

Ett nytt [DateTime](../)-objekt som representerar samma antal ticks som **value** och [DateTimeKind](../../datetimekind/)-värdet som anges av **kind**.

## Se även

* Class [DateTime](../)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
