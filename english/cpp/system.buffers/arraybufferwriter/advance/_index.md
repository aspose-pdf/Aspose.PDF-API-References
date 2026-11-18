---
title: System::Buffers::ArrayBufferWriter::Advance method
linktitle: Advance
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayBufferWriter::Advance method. Notifies the writer that count amount of data was written to the output Span/Memory in C++.'
type: docs
weight: 200
url: /cpp/system.buffers/arraybufferwriter/advance/
---
## ArrayBufferWriter::Advance method


Notifies the writer that **count** amount of data was written to the output Span/Memory.

```cpp
void System::Buffers::ArrayBufferWriter<T>::Advance(int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| count | int32_t | The number of elements that were written. |
## Remarks



You must request a new buffer after calling Advance to continue writing more data and cannot write to a previously acquired buffer. 

## See Also

* Class [ArrayBufferWriter](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
