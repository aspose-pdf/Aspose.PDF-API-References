---
title: System::Net::Security::SslStream::BeginWrite method
linktitle: BeginWrite
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::SslStream::BeginWrite method. Initiates an asynchronous write operation in C++.'
type: docs
weight: 400
url: /cpp/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite method


Initiates an asynchronous write operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The byte array to write data to. |
| offset | int32_t | The offset in bytes in the specified array. |
| count | int32_t | The number of bytes to write. |
| asyncCallback | AsyncCallback | A callback to be called when the operation completes. |
| asyncState | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous write operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous write operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
