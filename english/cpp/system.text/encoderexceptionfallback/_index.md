---
title: System::Text::EncoderExceptionFallback class
linktitle: EncoderExceptionFallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncoderExceptionFallback class. Provides exception-throwing fallback strategy. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.text/encoderexceptionfallback/
---
## EncoderExceptionFallback class


Provides exception-throwing fallback strategy. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderExceptionFallback : public System::Text::EncoderFallback
```

## Methods

| Method | Description |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Creates fallback buffer. |
| [EncoderExceptionFallback](./encoderexceptionfallback/)() | Constructor. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Gets maximal count of characters the instance can return. |
## See Also

* Class [EncoderFallback](../encoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
