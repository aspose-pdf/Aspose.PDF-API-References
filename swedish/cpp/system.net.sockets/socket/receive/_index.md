---
title: "System::Net::Sockets::Socket::Receive metod"
linktitle: "Mottag"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::Receive metod. Tar emot data från socketen och skriver den till den angivna bytearrayen i C++."
type: docs
weight: 4300
url: /sv/cpp/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| errorCode | SocketError\& | Den utdataparameter där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | int32_t | Antalet byte att ta emot. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| errorCode | SocketError\& | Den utdataparameter där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | int32_t | Antalet byte att ta emot. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte att ta emot som kommer att tilldelas den angivna bytearrayen från indexet 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| errorCode | SocketError\& | Den utdataparameter där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | int32_t | Antalet byte att ta emot. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Mottar data från socketen och skriver den till den angivna byte‑arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Mottar data från socketen och skriver den till de angivna byte‑arrayerna.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffertar | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Bytearrayerna där den mottagna datan kommer att tilldelas. |

### ReturnValue

Antalet byte som tas emot.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Mottar data från socketen och skriver den till de angivna byte‑arrayerna.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffertar | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Bytearrayerna där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Mottar data från socketen och skriver den till de angivna byte‑arrayerna.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffertar | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Bytearrayerna där den mottagna datan kommer att tilldelas. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| errorCode | SocketError\& | Den utdataparameter där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
