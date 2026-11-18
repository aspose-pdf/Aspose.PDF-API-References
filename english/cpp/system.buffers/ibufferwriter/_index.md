---
title: System::Buffers::IBufferWriter class
linktitle: IBufferWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::IBufferWriter class. Represents a sink for data, into which a consumer can write data. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.buffers/ibufferwriter/
---
## IBufferWriter class


Represents a sink for data, into which a consumer can write data. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IBufferWriter : public virtual System::Object
```


| Parameter | Description |
| --- | --- |
| T | The type of the element held by the writer. |
## Methods

| Method | Description |
| --- | --- |
| virtual [Advance](./advance/)(int32_t) | Notifies the [IBufferWriter](./) implementation that **count** elements were written to the output. |
| virtual [GetMemory](./getmemory/)(int32_t) | Returns a [Memory](../../system/memory/) that can be written to, and is guaranteed to have at least **sizeHint** elements. |
| virtual [GetSpan](./getspan/)(int32_t) | Returns a [Span](../../system/span/) that can be written to, and is guaranteed to have at least **sizeHint** elements. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
