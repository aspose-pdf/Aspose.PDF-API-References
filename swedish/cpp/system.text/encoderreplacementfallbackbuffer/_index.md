---
title: "System::Text::EncoderReplacementFallbackBuffer klass"
linktitle: "EncoderReplacementFallbackBuffer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncoderReplacementFallbackBuffer klass. Buffert för att ersätta kodningsfallback‑strategi. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1500
url: /sv/cpp/system.text/encoderreplacementfallbackbuffer/
---
## EncoderReplacementFallbackBuffer class


[Buffer](../../system/buffer/) for replacing encoding fallback strategy. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderReplacementFallbackBuffer : public System::Text::EncoderFallbackBuffer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EncoderReplacementFallbackBuffer](./encoderreplacementfallbackbuffer/)(const EncoderReplacementFallbackPtr\&) | Konstruktor. |
| [Fallback](./fallback/)(char_t, int) override | Hantera kodningsfel. |
| [Fallback](./fallback/)(char_t, char_t, int) override | Hantera kodningsfel. |
| [get_Remaining](./get_remaining/)() const override | Hämtar antalet återstående tecken i bufferten. |
| [GetNextChar](./getnextchar/)() override | Hämtar nästa tillgängliga tecken. |
| [MovePrevious](./moveprevious/)() override | Flyttar till föregående tecken. |
| [Reset](./reset/)() override | Återställer bufferten till ursprungligt tillstånd (innan [Fallback()](./fallback/) anrop). |
## Se även

* Class [EncoderFallbackBuffer](../encoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
