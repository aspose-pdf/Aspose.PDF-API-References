---
title: "System::Net::Sockets::Socket::IOControl metod"
linktitle: "IOControl"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::IOControl metod. Ställer in lågnivådriftslägen för socketen i C++."
type: docs
weight: 4000
url: /sv/cpp/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Ställer in lågnivådriftslägen för socketen.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ioControlCode | int32_t | Kontrollkoden för den operation som ska utföras. |
| optionInValue | System::ArrayPtr\<uint8_t\> | Bytearrayen som innehåller indata. |
| optionOutValue | System::ArrayPtr\<uint8_t\> | Bytearrayen som innehåller utdata. |

### ReturnValue

Antalet byte i parametern **optionOutValue**.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Ställer in lågnivådriftslägen för socketen.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ioControlCode | IOControlCode | Kontrollkoden för den operation som ska utföras. |
| optionInValue | System::ArrayPtr\<uint8_t\> | Bytearrayen som innehåller indata. |
| optionOutValue | System::ArrayPtr\<uint8_t\> | Bytearrayen som innehåller utdata. |

### ReturnValue

Antalet byte i parametern **optionOutValue**.

## Se även

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
