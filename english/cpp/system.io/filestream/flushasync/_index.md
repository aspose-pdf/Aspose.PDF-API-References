---
title: System::IO::FileStream::FlushAsync method
linktitle: FlushAsync
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileStream::FlushAsync method. Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests in C++.'
type: docs
weight: 500
url: /cpp/system.io/filestream/flushasync/
---
## FileStream::FlushAsync method


Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | const Threading::CancellationToken\& | The token to monitor for cancellation requests. |

### ReturnValue

A task that represents the asynchronous flush operation.

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
