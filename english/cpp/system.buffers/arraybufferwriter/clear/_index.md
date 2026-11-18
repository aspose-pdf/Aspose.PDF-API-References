---
title: System::Buffers::ArrayBufferWriter::Clear method
linktitle: Clear
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayBufferWriter::Clear method. Clears the data written to the underlying buffer in C++.'
type: docs
weight: 300
url: /cpp/system.buffers/arraybufferwriter/clear/
---
## ArrayBufferWriter::Clear method


Clears the data written to the underlying buffer.

```cpp
void System::Buffers::ArrayBufferWriter<T>::Clear()
```

## Remarks



You must reset or clear the [ArrayBufferWriter](../) before trying to re-use it. 

The ResetWrittenCount method is faster since it only sets to zero the writer's index while the Clear method additionally zeroes the content of the underlying buffer. 

## See Also

* Class [ArrayBufferWriter](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
