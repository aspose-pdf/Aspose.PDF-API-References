---
title: System::Text::DecoderExceptionFallbackBuffer class
linktitle: DecoderExceptionFallbackBuffer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::DecoderExceptionFallbackBuffer class. Buffer for exception-throwing decoding fallback strategy. Doesn''t store anything actually, but throws instead. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.text/decoderexceptionfallbackbuffer/
---
## DecoderExceptionFallbackBuffer class


[Buffer](../../system/buffer/) for exception-throwing decoding fallback strategy. Doesn't store anything actually, but throws instead. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DecoderExceptionFallbackBuffer : public System::Text::DecoderFallbackBuffer
```

## Methods

| Method | Description |
| --- | --- |
| [DecoderExceptionFallbackBuffer](./decoderexceptionfallbackbuffer/)() | Constructor. |
| [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) override | Handles decoding failure. |
| [get_Remaining](./get_remaining/)() const override | Gets number of remaining characters. |
| [GetNextChar](./getnextchar/)() override | Gets next available character. |
| [MovePrevious](./moveprevious/)() override | Moves to previous chracter. |
## See Also

* Class [DecoderFallbackBuffer](../decoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
