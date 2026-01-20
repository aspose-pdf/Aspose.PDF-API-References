---
title: System::Net::Sockets::Socket::EndSend method
linktitle: EndSend
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::EndSend method. Waits until the specified asynchronous send operation completes in C++.'
type: docs
weight: 1600
url: /cpp/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous send operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous send operation. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Waits until the specified asynchronous send operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous send operation. |
| errorCode | SocketError\& | The output parameter where the error code will be assigned when the send operation fails. |

### ReturnValue

The number of sent bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
