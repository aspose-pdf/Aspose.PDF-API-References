---
title: "System::IO::MemoryStream::Write method"
linktitle: "Write"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::MemoryStream::Write method. Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen i C++."
type: docs
weight: 1900
url: /sv/cpp/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Arrayen som innehåller byte att skriva. |
| förskjutning | int32_t | Ett 0-baserat index för elementet i **buffer** där delområdet att skriva börjar |
| count | int32_t | Antalet element i delintervallet som ska skrivas |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Arrayvyn som innehåller byte att skriva |
| förskjutning | int32_t | Ett 0-baserat index för elementet i **buffer** där delområdet att skriva börjar |
| count | int32_t | Antalet element i delintervallet som ska skrivas |

## Se även

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
