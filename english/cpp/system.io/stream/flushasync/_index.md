---
title: System::IO::Stream::FlushAsync method
linktitle: FlushAsync
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Stream::FlushAsync method. Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests in C++.'
type: docs
weight: 900
url: /cpp/system.io/stream/flushasync/
---
## Stream::FlushAsync() method


Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### ReturnValue

A task that represents the asynchronous flush operation.

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::FlushAsync(const Threading::CancellationToken\&) method


Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | const Threading::CancellationToken\& | The token to monitor for cancellation requests. |

### ReturnValue

A task that represents the asynchronous flush operation.

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
