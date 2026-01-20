---
title: System::Net::Sockets::NetworkStream::BeginRead method
linktitle: BeginRead
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::NetworkStream::BeginRead method. Initiates an asynchronous read operation in C++.'
type: docs
weight: 300
url: /cpp/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead method


Initiates an asynchronous read operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The byte array where the read bytes will be written. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes to read. |
| callback | AsyncCallback | A callback to be called when the operation completes. |
| state | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous read operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous read operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
