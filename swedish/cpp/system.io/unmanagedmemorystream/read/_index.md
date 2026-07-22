---
title: "System::IO::UnmanagedMemoryStream::Read‑metod"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::UnmanagedMemoryStream::Read‑metod. Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte‑arrayen i C++."
type: docs
weight: 1000
url: /sv/cpp/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
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
* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Byte‑arrayvyn att skriva de lästa byten till |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| count | int32_t | Antalet byte att läsa |

### ReturnValue

Antalet byte som lästs

## Se även

* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
