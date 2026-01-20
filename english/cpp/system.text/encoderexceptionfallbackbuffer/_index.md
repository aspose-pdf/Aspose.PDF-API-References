---
title: System::Text::EncoderExceptionFallbackBuffer class
linktitle: EncoderExceptionFallbackBuffer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncoderExceptionFallbackBuffer class. Buffer for exception-throwing encoding fallback strategy. Doesn''t store anything actually, but throws instead. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.text/encoderexceptionfallbackbuffer/
---
## EncoderExceptionFallbackBuffer class


[Buffer](../../system/buffer/) for exception-throwing encoding fallback strategy. Doesn't store anything actually, but throws instead. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderExceptionFallbackBuffer : public System::Text::EncoderFallbackBuffer
```

## Methods

| Method | Description |
| --- | --- |
| [EncoderExceptionFallbackBuffer](./encoderexceptionfallbackbuffer/)() | Constructor. |
| [Fallback](./fallback/)(char_t, int) override | Handles encoding failure. |
| [Fallback](./fallback/)(char_t, char_t, int) override | Handles encoding failure. |
| [get_Remaining](./get_remaining/)() const override | Gets number of remaining characters. |
| [GetNextChar](./getnextchar/)() override | Gets next available character. |
| [MovePrevious](./moveprevious/)() override | Moves to previous chracter. |
## See Also

* Class [EncoderFallbackBuffer](../encoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
