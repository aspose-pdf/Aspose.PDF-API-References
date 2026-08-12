---
title: "System::IO::Stream::Write‑metod"
linktitle: "Write"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Stream::Write‑metod. Skriver det angivna delintervallet av byte från den angivna byte‑arrayen till strömmen i C++."
type: docs
weight: 2600
url: /sv/cpp/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Arrayen som innehåller byte att skriva. |
| förskjutning | int32_t | Ett 0‑baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | int32_t | Antalet element i delintervallet som ska skrivas |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Arrayvyn som innehåller byte att skriva |
| förskjutning | int32_t | Ett 0‑baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | int32_t | Antalet element i delintervallet som ska skrivas |

## Se även

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


| Parameter | Beskrivning |
| --- | --- |
| N | Storleken på stackarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<uint8_t, N\>\& | Stack‑arrayen som innehåller byte som ska skrivas |
| förskjutning | int32_t | Ett 0‑baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | int32_t | Antalet element i delintervallet som ska skrivas |

## Se även

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method


Skriver det angivna delintervallet av bytes från det angivna byte-området till strömmen.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::ReadOnlySpan\<uint8_t\>\& | Byte‑spannet att läsa de skrivna byten från |

## Se även

* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
