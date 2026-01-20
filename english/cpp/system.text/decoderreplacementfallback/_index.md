---
title: System::Text::DecoderReplacementFallback class
linktitle: DecoderReplacementFallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::DecoderReplacementFallback class. Provides fallback strategy of replacing erroneous symbol with a stub. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.text/decoderreplacementfallback/
---
## DecoderReplacementFallback class


Provides fallback strategy of replacing erroneous symbol with a stub. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DecoderReplacementFallback : public System::Text::DecoderFallback
```

## Methods

| Method | Description |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Creates fallback buffer. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)() | Constructor that uses deafault "?" replacement string. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)(const String\&) | Constructor. |
| [get_DefaultString](./get_defaultstring/)() const | Gets replacement string. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Gets maximal count of characters the instance can return. |
## See Also

* Class [DecoderFallback](../decoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
