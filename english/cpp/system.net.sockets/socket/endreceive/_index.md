---
title: System::Net::Sockets::Socket::EndReceive method
linktitle: EndReceive
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::EndReceive method. Waits until the specified asynchronous receive operation completes in C++.'
type: docs
weight: 1500
url: /cpp/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous receive operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |

### ReturnValue

The number of bytes that are received.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Waits until the specified asynchronous receive operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |
| errorCode | SocketError\& | The output parameter where the error code will be assigned when the receive operation fails. |

### ReturnValue

The number of received bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
