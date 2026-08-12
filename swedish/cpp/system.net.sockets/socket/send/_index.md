---
title: "System::Net::Sockets::Socket::Send method"
linktitle: "Skicka"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::Send method. Skickar den angivna datan till socketen i C++."
type: docs
weight: 4600
url: /sv/cpp/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Datan att skicka. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Datan att skicka. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Datan att skicka. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Sändningsbeteendet. |
| errorCode | SocketError\& | Utdata‑parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Datan att skicka. |
| size | int32_t | Antalet byte från den angivna datan som måste skickas. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Datan att skicka. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Datan att skicka. |

### ReturnValue

Antalet skickade byte.

## Se även

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Datan att skicka. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Datan att skicka. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Sändningsbeteendet. |
| errorCode | SocketError\& | Utdata‑parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Datan att skicka. |
| size | int32_t | Antalet byte från den angivna datan som måste skickas. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Datan att skicka. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method


Skickar den angivna datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Datan att skicka. |

### ReturnValue

Antalet skickade byte.

## Se även

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Datan att skicka. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Skickar den angivna datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Datan att skicka. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Sändningsbeteendet. |
| errorCode | SocketError\& | Utdata‑parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Datan att skicka. |
| size | int32_t | Antalet byte från den angivna datan som måste skickas. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Datan att skicka. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffertar | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | En samling av byte-arrayer från vilka data måste skickas. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffertar | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | En samling av byte-arrayer från vilka data måste skickas. |
| socketFlags | SocketFlags | Sändningsbeteendet. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Skickar den angivna datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffertar | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | En samling av byte-arrayer från vilka data måste skickas. |
| socketFlags | SocketFlags | Sändningsbeteendet. |
| errorCode | SocketError\& | Utdata‑parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
