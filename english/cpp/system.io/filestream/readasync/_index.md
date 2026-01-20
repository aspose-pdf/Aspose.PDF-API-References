---
title: System::IO::FileStream::ReadAsync method
linktitle: ReadAsync
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileStream::ReadAsync method. Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests in C++.'
type: docs
weight: 1400
url: /cpp/system.io/filestream/readasync/
---
## FileStream::ReadAsync method


Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | The byte array to write the read bytes to. |
| offset | int32_t | A 0-based position in **buffer** to start writing at. |
| count | int32_t | The number of bytes to read. |
| cancellationToken | const Threading::CancellationToken\& | The token to monitor for cancellation requests. |

### ReturnValue

A task that represents the asynchronous read operation. The value of the TResult parameter contains the total number of bytes read into the buffer. The result value can be less than the number of bytes requested if the number of bytes currently available is less than the requested number, or it can be 0 (zero) if the end of the stream has been reached.

## See Also

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
