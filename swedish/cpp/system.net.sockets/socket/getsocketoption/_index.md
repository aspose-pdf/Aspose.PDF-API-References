---
title: "System::Net::Sockets::Socket::GetSocketOption metod"
linktitle: "GetSocketOption"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::GetSocketOption metod. Returnerar värdet som motsvarar det angivna alternativnamnet i C++."
type: docs
weight: 3900
url: /sv/cpp/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) method


Returnerar värdet som motsvarar det angivna alternativnamnet.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | Socket‑alternativnivån. |
| optionName | SocketOptionName | Alternativnamnet. |

### ReturnValue

Värdet som motsvarar det angivna alternativnamnet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


Returnerar värdet som motsvarar det angivna alternativnamnet.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | Socket‑alternativnivån. |
| optionName | SocketOptionName | Alternativnamnet. |
| optionLength | int32_t | Alternativlängden. |

### ReturnValue

Värdet som motsvarar det angivna alternativnamnet.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


Hämtar värdet som motsvarar det angivna alternativnamnet.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | Socket‑alternativnivån. |
| optionName | SocketOptionName | Alternativnamnet. |
| optionValue | System::ArrayPtr\<uint8_t\> | Utdataparameter där motsvarande värde kommer att tilldelas. |

## Se även

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
