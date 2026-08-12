---
title: "System::IO::Stream::Read‑metod"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Stream::Read‑metod. Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte‑arrayen i C++."
type: docs
weight: 1800
url: /sv/cpp/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
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
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Byte‑arrayvyn att skriva de lästa byten till |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| count | int32_t | Antalet byte att läsa |

### ReturnValue

Antalet byte som lästs

## Se även

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


| Parameter | Beskrivning |
| --- | --- |
| N | Storleken på stackarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<uint8_t, N\>\& | Byte‑stack‑arrayen att skriva de lästa byten till |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| count | int32_t | Antalet byte att läsa |

### ReturnValue

Antalet byte som lästs

## Se även

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Read(const System::Span\<uint8_t\>\&) method


Läser det angivna antalet byte från strömmen och skriver dem till det angivna byte‑spannet.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Span\<uint8_t\>\& | Byte‑spannet att skriva de lästa byten till |

### ReturnValue

Antalet byte som lästs

## Se även

* Class [Span](../../../system/span/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
