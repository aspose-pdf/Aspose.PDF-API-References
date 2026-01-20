---
title: System::Text::DecoderReplacementFallbackBuffer class
linktitle: DecoderReplacementFallbackBuffer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::DecoderReplacementFallbackBuffer class. Buffer for replacing decoding fallback strategy in C++.'
type: docs
weight: 800
url: /cpp/system.text/decoderreplacementfallbackbuffer/
---
## DecoderReplacementFallbackBuffer class


[Buffer](../../system/buffer/) for replacing decoding fallback strategy.

```cpp
class DecoderReplacementFallbackBuffer : public System::Text::DecoderFallbackBuffer
```

## Methods

| Method | Description |
| --- | --- |
| [DecoderReplacementFallbackBuffer](./decoderreplacementfallbackbuffer/)(const DecoderReplacementFallbackPtr\&) | Constructor. |
| [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) override | Handles decoding failure. |
| [get_Remaining](./get_remaining/)() const override | Gets number of remaining characters in buffer. |
| [GetNextChar](./getnextchar/)() override | Gets next available character. |
| [MovePrevious](./moveprevious/)() override | Moves to previous chracter. |
| [Reset](./reset/)() override | Resets buffer to initial state (before [Fallback()](./fallback/) call). |
## See Also

* Class [DecoderFallbackBuffer](../decoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
