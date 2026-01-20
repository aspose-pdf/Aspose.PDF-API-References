---
title: System::Net::Sockets::NetworkStream::NetworkStream constructor
linktitle: NetworkStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::NetworkStream::NetworkStream constructor. Constructs a new instance in C++.'
type: docs
weight: 100
url: /cpp/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```


| Parameter | Type | Description |
| --- | --- | --- |
| socket | System::SharedPtr\<System::Net::Sockets::Socket\> | The socket that is used for sending and receiving data. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```


| Parameter | Type | Description |
| --- | --- | --- |
| socket | System::SharedPtr\<System::Net::Sockets::Socket\> | The socket that is used for sending and receiving data. |
| ownsSocket | bool | A value that indicates if the current instance takes ownership of the specified socket when the value is true. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```


| Parameter | Type | Description |
| --- | --- | --- |
| socket | System::SharedPtr\<System::Net::Sockets::Socket\> | The socket that is used for sending and receiving data. |
| access | System::IO::FileAccess | Specifies the access type given to the instance over the specified socket. |
| ownsSocket | bool | A value that indicates if the current instance takes ownership of the specified socket when the value is true. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
