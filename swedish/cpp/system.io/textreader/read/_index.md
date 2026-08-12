---
title: "System::IO::TextReader::Read metod"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::TextReader::Read metod. Läser ett enda tecken från strömmen i C++."
type: docs
weight: 400
url: /sv/cpp/system.io/textreader/read/
---
## TextReader::Read() method


Läser ett enskilt tecken från strömmen.

```cpp
virtual int System::IO::TextReader::Read()
```


### ReturnValue

Läs tecken kodade med UTF-16-kodning; om det lästa tecknet representeras av två kodpunkter i UTF-16-kodning returneras endast den högre surrogaten.

## Se även

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextReader::Read(ArrayPtr\<char_t\>, int, int) method


Läser det angivna antalet tecken från strömmen och skriver dem till den angivna teckenarrayen med start vid den angivna positionen.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
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
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
