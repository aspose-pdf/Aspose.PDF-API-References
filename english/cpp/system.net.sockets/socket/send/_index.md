---
title: System::Net::Sockets::Socket::Send method
linktitle: Send
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::Send method. Sends the specified data to the socket in C++.'
type: docs
weight: 4600
url: /cpp/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |
| errorCode | SocketError\& | The output parameter where the error code will be assigned when the send operation fails. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| size | int32_t | The number of bytes from the specified data that must be send. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |

### ReturnValue

The number of sent bytes.

## See Also

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |
| errorCode | SocketError\& | The output parameter where the error code will be assigned when the send operation fails. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| size | int32_t | The number of bytes from the specified data that must be send. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |

### ReturnValue

The number of sent bytes.

## See Also

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |
| errorCode | SocketError\& | The output parameter where the error code will be assigned when the send operation fails. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| size | int32_t | The number of bytes from the specified data that must be send. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffers | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | A collection of byte arrays from which data must be sent. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffers | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | A collection of byte arrays from which data must be sent. |
| socketFlags | SocketFlags | The send behavior. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffers | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | A collection of byte arrays from which data must be sent. |
| socketFlags | SocketFlags | The send behavior. |
| errorCode | SocketError\& | The output parameter where the error code will be assigned when the send operation fails. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
