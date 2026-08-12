---
title: "System::Net::Security::SslStream::Read method"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::SslStream::Read method. Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen i C++."
type: docs
weight: 3200
url: /sv/cpp/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Bytearrayen att skriva de lästa byten till. |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| count | int32_t | Antalet byte att läsa |

### ReturnValue

Antalet byte som lästs

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Bytearrayen att skriva de lästa byten till. |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| count | int32_t | Antalet byte att läsa |

### ReturnValue

Antalet byte som lästs

## Se även

* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
