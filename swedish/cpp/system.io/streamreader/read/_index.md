---
title: "System::IO::StreamReader::Read‑metod"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StreamReader::Read‑metod. Läser ett enda tecken från strömmen i C++."
type: docs
weight: 900
url: /sv/cpp/system.io/streamreader/read/
---
## StreamReader::Read() method


Läser ett enskilt tecken från strömmen.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### ReturnValue

Läs tecken kodade med UTF-16-kodning; om det lästa tecknet representeras av två kodpunkter i UTF-16-kodning returneras endast den högre surrogaten.

## Se även

* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::Read(ArrayPtr\<char_t\>, int, int) method


Läser det angivna antalet tecken från strömmen, konverterar dem till UTF‑16‑kodning och skriver de resulterande UTF‑16‑tecknen till den angivna teckenarrayen med start på den angivna positionen.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | Den UTF-16-teckenarray som tecknen som lästs från strömmen ska skrivas till. |
| index | int | Ett 0-baserat index i **buffer** där skrivning ska börja |
| count | int | Antalet tecken att läsa från strömmen |

### ReturnValue

Antalet tecken som lästs från strömmen

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
