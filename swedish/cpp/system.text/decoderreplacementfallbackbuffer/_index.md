---
title: "System::Text::DecoderReplacementFallbackBuffer klass"
linktitle: "DecoderReplacementFallbackBuffer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::DecoderReplacementFallbackBuffer klass. Buffer för att ersätta avkodningsreservstrategi i C++."
type: docs
weight: 800
url: /sv/cpp/system.text/decoderreplacementfallbackbuffer/
---
## DecoderReplacementFallbackBuffer class


[Buffer](../../system/buffer/) for replacing decoding fallback strategy.

```cpp
class DecoderReplacementFallbackBuffer : public System::Text::DecoderFallbackBuffer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DecoderReplacementFallbackBuffer](./decoderreplacementfallbackbuffer/)(const DecoderReplacementFallbackPtr\&) | Konstruktor. |
| [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) override | Hantera avkodningsfel. |
| [get_Remaining](./get_remaining/)() const override | Hämtar antalet återstående tecken i bufferten. |
| [GetNextChar](./getnextchar/)() override | Hämtar nästa tillgängliga tecken. |
| [MovePrevious](./moveprevious/)() override | Flyttar till föregående tecken. |
| [Reset](./reset/)() override | Återställer bufferten till ursprungligt tillstånd (innan [Fallback()](./fallback/) anrop). |
## Se även

* Class [DecoderFallbackBuffer](../decoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
