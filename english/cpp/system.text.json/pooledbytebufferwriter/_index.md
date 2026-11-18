---
title: System::Text::Json::PooledByteBufferWriter class
linktitle: PooledByteBufferWriter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::PooledByteBufferWriter class in C++.'
type: docs
weight: 2300
url: /cpp/system.text.json/pooledbytebufferwriter/
---
## PooledByteBufferWriter class




```cpp
class PooledByteBufferWriter : public System::Buffers::IBufferWriter<uint8_t>,
                               public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Advance](./advance/)(int32_t) override | Notifies the IBufferWriter implementation that **count** elements were written to the output. |
| [Clear](./clear/)() |  |
| [ClearAndReturnBuffers](./clearandreturnbuffers/)() |  |
| static [CreateEmptyInstanceForCaching](./createemptyinstanceforcaching/)() |  |
| [Dispose](./dispose/)() override | Does nothing. |
| [get_CanGetUnflushedBytes](./get_cangetunflushedbytes/)() |  |
| [get_Capacity](./get_capacity/)() |  |
| [get_UnflushedBytes](./get_unflushedbytes/)() |  |
| [get_WrittenMemory](./get_writtenmemory/)() |  |
| [get_WrittenSpan](./get_writtenspan/)() |  |
| [GetMemory](./getmemory/)(int32_t) override | Returns a [Memory](../../system/memory/) that can be written to, and is guaranteed to have at least **sizeHint** elements. |
| [GetSpan](./getspan/)(int32_t) override | Returns a [Span](../../system/span/) that can be written to, and is guaranteed to have at least **sizeHint** elements. |
| [InitializeEmptyInstance](./initializeemptyinstance/)(int32_t) |  |
| [PooledByteBufferWriter](./pooledbytebufferwriter/)(int32_t) |  |
| [WriteToStream](./writetostream/)(System::SharedPtr\<IO::Stream\>) |  |
## See Also

* Class [IBufferWriter](../../system.buffers/ibufferwriter/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
