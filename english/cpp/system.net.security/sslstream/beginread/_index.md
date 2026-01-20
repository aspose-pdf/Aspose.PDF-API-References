---
title: System::Net::Security::SslStream::BeginRead method
linktitle: BeginRead
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::SslStream::BeginRead method. Initiates an asynchronous read operation in C++.'
type: docs
weight: 300
url: /cpp/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead method


Initiates an asynchronous read operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | The byte array to read data from. |
| offset | int32_t | The offset in bytes in the specified array. |
| count | int32_t | The number of bytes to read. |
| asyncCallback | AsyncCallback | A callback to be called when the operation completes. |
| asyncState | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous read operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous read operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
