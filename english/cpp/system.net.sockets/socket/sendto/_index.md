---
title: System::Net::Sockets::Socket::SendTo method
linktitle: SendTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::SendTo method. Sends the specified data to the specified endpoint in C++.'
type: docs
weight: 4700
url: /cpp/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| size | int32_t | The number of bytes in the specified array. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The data to send. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| size | int32_t | The number of bytes in the specified array. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | The data to send. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| size | int32_t | The number of bytes in the specified array. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| socketFlags | SocketFlags | The send behavior. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Sends the specified data to the specified endpoint.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | The data to send. |
| remoteEP | System::SharedPtr\<EndPoint\> | The remote endpoint. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
