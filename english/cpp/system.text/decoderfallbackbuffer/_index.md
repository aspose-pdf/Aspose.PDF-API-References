---
title: System::Text::DecoderFallbackBuffer class
linktitle: DecoderFallbackBuffer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::DecoderFallbackBuffer class. Provides buffer for fallback implementation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.text/decoderfallbackbuffer/
---
## DecoderFallbackBuffer class


Provides buffer for fallback implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DecoderFallbackBuffer : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) | Implements actual fallback procedure. |
| virtual [get_Remaining](./get_remaining/)() const | Gets remaining count of characters to be processed. |
| virtual [GetNextChar](./getnextchar/)() | Extracts next character in fallback buffer. |
| virtual [MovePrevious](./moveprevious/)() | Moves buffer position one step back if possible. |
| virtual [Reset](./reset/)() | Resets buffer to initial state. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
