---
title: System::IO::Stream::BeginRead method
linktitle: BeginRead
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Stream::BeginRead method. Initiates an asynchronous read operation in C++.'
type: docs
weight: 100
url: /cpp/system.io/stream/beginread/
---
## Stream::BeginRead method


Initiates an asynchronous read operation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | A buffer to read to |
| offset | int | A 0-based offset in **buffer** indicating the position from which to start writing the read data |
| count | int | The number of bytes to read |
| callback | System::AsyncCallback | A callback to be called when the operation completes |
| state | System::SharedPtr\<System::Object\> | User-provided data used to uniquely identify each asynchronous read operation |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous read operation

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
