---
title: System::Text::EncoderFallback class
linktitle: EncoderFallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncoderFallback class. Provides fallback API to handle encoding error. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.text/encoderfallback/
---
## EncoderFallback class


Provides fallback API to handle encoding error. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderFallback : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CreateFallbackBuffer](./createfallbackbuffer/)() | Gets buffer associated with fallback algorithm. |
| static [get_ExceptionFallback](./get_exceptionfallback/)() | Gets default exception fallback implementation. |
| virtual [get_MaxCharCount](./get_maxcharcount/)() const | Gets maximal number of characters that can be returned by fallback. |
| static [get_ReplacementFallback](./get_replacementfallback/)() | Gets default replacement fallback implementation. |
| static [get_StandardSafeFallback](./get_standardsafefallback/)() | Gets default standard safe fallback implementation. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
