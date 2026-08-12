---
title: "System::Net::Sockets::NetworkStream::Write metod"
linktitle: "Write"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::NetworkStream::Write metod. Skriver det angivna delintervallet av byte från den angivna byte‑arrayen till strömmen i C++."
type: docs
weight: 2500
url: /sv/cpp/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Arrayen som innehåller byte att skriva. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet element i delintervallet som ska skrivas. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Arrayvyn som innehåller byte att skriva |
| förskjutning | int32_t | Ett 0‑baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| size | int32_t | Antalet element i delintervallet som ska skrivas |

## Se även

* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
