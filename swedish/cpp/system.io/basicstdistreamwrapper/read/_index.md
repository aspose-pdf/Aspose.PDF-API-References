---
title: "System::IO::BasicSTDIStreamWrapper::Read‑metod"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BasicSTDIStreamWrapper::Read‑metod. Om omslagsläget är binärt, läses det angivna antalet byte från strömmen, annars läses det angivna antalet tecken och konverteras till typen uint8_t. Resultatet av läsningen skrivs till den angivna byte‑arrayen i C++."
type: docs
weight: 400
url: /sv/cpp/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Om omslagsläget är binärt läses det angivna antalet bytes från strömmen, annars läses det angivna antalet tecken och konverteras till uint8_t-typ. Skriver resultatet av läsningen till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Bytearrayen att skriva de lästa byten till. |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| count | int32_t | Antalet byte att läsa |

### ReturnValue

Antal byte eller tecken lästa

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Byte‑arrayvyn att skriva de lästa byten till |
| förskjutning | int32_t | En 0‑baserad position i **buffer** att börja skriva på |
| count | int32_t | Antalet byte att läsa |

### ReturnValue

Antalet byte som lästs

## Se även

* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
