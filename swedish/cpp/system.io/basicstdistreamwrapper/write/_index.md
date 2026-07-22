---
title: "System::IO::BasicSTDIStreamWrapper::Write‑metod"
linktitle: "Write"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BasicSTDIStreamWrapper::Write‑metod. Om omslagsläget är binärt, skriver den angivna delintervallet av byte från den angivna byte‑arrayen till strömmen, annars konverteras det angivna delintervallet av byte från den angivna byte‑arrayen till typen char_type och resultatet skrivs sedan till strömmen. Stöds inte! i C++."
type: docs
weight: 700
url: /sv/cpp/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Om omslagsläget är binärt, skriver den angivna delintervallet av byte från den angivna byte‑arrayen till strömmen, annars konverteras det angivna delintervallet av byte från den angivna byte‑arrayen till [char_type](../char_type/)-typen och resultatet skrivs sedan till strömmen. Stöds inte!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Arrayen som innehåller byte att skriva. |
| förskjutning | int32_t | Ett 0‑baserat index för elementet i **buffer** där delintervallet att skriva börjar. |
| count | int32_t | Antalet element i delintervallet som ska skrivas. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Arrayvyn som innehåller byte att skriva |
| förskjutning | int32_t | Ett 0‑baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | int32_t | Antalet element i delintervallet som ska skrivas |

## Se även

* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
