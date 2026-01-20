---
title: System::IO::Stream::BeginWrite method
linktitle: BeginWrite
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Stream::BeginWrite method. Initiates an asynchronous write operation in C++.'
type: docs
weight: 200
url: /cpp/system.io/stream/beginwrite/
---
## Stream::BeginWrite method


Initiates an asynchronous write operation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | A buffer containing data to be written |
| offset | int | A 0-based offset in **buffer** indicating the position from which the data to write begins |
| count | int | The number of bytes to write |
| callback | System::AsyncCallback | A callback to be called when the operation completes |
| state | System::SharedPtr\<System::Object\> | User-provided data used to uniquely identify each asynchronous write operation |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous write operation

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
