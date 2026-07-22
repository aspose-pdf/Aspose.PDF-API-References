---
title: "System::Globalization::DateTimeStyles enum"
linktitle: "DateTimeStyles"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::DateTimeStyles enum. Definierar datum- och tidsformateringsalternativ. Bitflaggor i C++."
type: docs
weight: 3500
url: /sv/cpp/system.globalization/datetimestyles/
---
## DateTimeStyles enum


Definierar datum- och tidsformateringsalternativ. Bitflaggor.

```cpp
enum class DateTimeStyles : int32_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Standard. |
| AllowLeadingWhite | 1 | Ignorera inledande blanksteg. |
| AllowTrailingWhite | 2 | Ignorera avslutande blanksteg. |
| AllowInnerWhite | 4 | Ignorera inre blanksteg. |
| AllowWhiteSpaces | n/a | Ignorera alla blanksteg. |
| NoCurrentDateDefault | 8 | När du analyserar en datum/tidssträng, om alla år/månad/dag saknas, sätt standarddatumet till 0001/1/1, istället för det aktuella år/månad/dag. |
| AdjustToUniversal | 16 | När du analyserar en datum/tidssträng, om en tidszonspecifikation (\"GMT\",\"Z\",\"+xxxx\", \"-xxxx\" finns), kommer vi att justera den analyserade tiden baserat på GMT. |
| AssumeLocal | 32 | Om ingen tidszon anges, använd lokal tidszon. |
| AssumeUniversal | 64 | Om ingen tidszon anges, använd UTC. |
| RoundtripKind | 128 | Försök att bevara om indata är ospecificerad, lokal eller UTC. |

## Se även

* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
