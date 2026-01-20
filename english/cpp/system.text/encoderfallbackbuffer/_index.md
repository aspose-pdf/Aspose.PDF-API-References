---
title: System::Text::EncoderFallbackBuffer class
linktitle: EncoderFallbackBuffer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncoderFallbackBuffer class. Provides buffer for fallback implementation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.text/encoderfallbackbuffer/
---
## EncoderFallbackBuffer class


Provides buffer for fallback implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderFallbackBuffer : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Fallback](./fallback/)(char_t, int) | Implements actual fallback procedure. |
| virtual [Fallback](./fallback/)(char_t, char_t, int) | Implements actual fallback procedure. |
| virtual [get_Remaining](./get_remaining/)() const | Gets remaining count of characters to be processed. |
| virtual [GetNextChar](./getnextchar/)() | Extracts next character in fallback buffer. |
| virtual [MovePrevious](./moveprevious/)() | Moves buffer position one step back if possible. |
| virtual [Reset](./reset/)() | Resets buffer to initial state. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
