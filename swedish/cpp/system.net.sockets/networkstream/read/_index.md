---
title: "System::Net::Sockets::NetworkStream::Read metod"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::NetworkStream::Read metod. Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte‑arrayen i C++."
type: docs
weight: 1900
url: /sv/cpp/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Bytearrayen där de lästa byten kommer att skrivas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att läsa. |

### ReturnValue

Antalet lästa byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Byte‑arrayvyn att skriva de lästa byten till |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| size | int32_t | Antalet byte att läsa |

### ReturnValue

Antalet byte som lästs

## Se även

* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
