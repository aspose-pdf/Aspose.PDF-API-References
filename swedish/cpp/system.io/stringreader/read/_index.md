---
title: "System::IO::StringReader::Read metod"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StringReader::Read metod. Läser ett enda tecken från strömmen i C++."
type: docs
weight: 500
url: /sv/cpp/system.io/stringreader/read/
---
## StringReader::Read() method


Läser ett enskilt tecken från strömmen.

```cpp
virtual int System::IO::StringReader::Read() override
```


### ReturnValue

Ett läst tecken eller -1 om inget tecken har lästs

## Se även

* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StringReader::Read(ArrayPtr\<char_t\>, int, int) method


Läser det angivna antalet tecken från strömmen till den angivna teckenarrayen med start vid den angivna positionen.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | Teckenarrayen att skriva de lästa tecknen från strömmen till |
| index | int | Ett 0-baserat index i **buffer** där skrivning ska börja |
| count | int | Antalet tecken att läsa från strömmen |

### ReturnValue

Antalet tecken som lästs från strömmen

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
