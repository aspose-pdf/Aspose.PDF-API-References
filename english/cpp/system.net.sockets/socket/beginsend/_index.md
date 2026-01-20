---
title: System::Net::Sockets::Socket::BeginSend method
linktitle: BeginSend
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::BeginSend method. Initiates an asynchronous send operation in C++.'
type: docs
weight: 900
url: /cpp/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend method


Initiates an asynchronous send operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | A buffer to read data from. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | SocketFlags | The send behaviour. |
| callback | AsyncCallback | A callback that will be called when the operation completes. |
| state | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous send operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous send operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
