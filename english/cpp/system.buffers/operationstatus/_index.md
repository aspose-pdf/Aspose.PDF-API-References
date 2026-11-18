---
title: System::Buffers::OperationStatus enum
linktitle: OperationStatus
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::OperationStatus enum. Represents the status of an operation that processes a buffer in C++.'
type: docs
weight: 1100
url: /cpp/system.buffers/operationstatus/
---
## OperationStatus enum


Represents the status of an operation that processes a buffer.

```cpp
enum class OperationStatus
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Done | 0 | The operation completed successfully. |
| DestinationTooSmall | 1 | The operation did not fully complete because the destination buffer was too small. |
| NeedMoreData | 2 | The operation did not fully complete because more input is needed to continue. |
| InvalidData | 3 | The operation did not fully complete because the input contained invalid data. |

## See Also

* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
