---
title: "System::Net::Sockets::Socket::ReceiveFrom metod"
linktitle: "ReceiveFrom"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::ReceiveFrom metod. Tar emot data från den angivna slutpunkten och skriver den till den angivna bytearrayen i C++."
type: docs
weight: 4400
url: /sv/cpp/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method


Mottar data från den angivna slutpunkten och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Den fjärrslutpunkten. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
