---
title: "System::Text::EncoderExceptionFallbackBuffer-klass"
linktitle: "EncoderExceptionFallbackBuffer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncoderExceptionFallbackBuffer-klass. Buffer för undantagskastande kodningsfallback‑strategi. Lagrar faktiskt ingenting, men kastar ett undantag istället. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.text/encoderexceptionfallbackbuffer/
---
## EncoderExceptionFallbackBuffer class


[Buffer](../../system/buffer/) for exception-throwing encoding fallback strategy. Doesn't store anything actually, but throws instead. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderExceptionFallbackBuffer : public System::Text::EncoderFallbackBuffer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EncoderExceptionFallbackBuffer](./encoderexceptionfallbackbuffer/)() | Konstruktor. |
| [Fallback](./fallback/)(char_t, int) override | Hantera kodningsfel. |
| [Fallback](./fallback/)(char_t, char_t, int) override | Hantera kodningsfel. |
| [get_Remaining](./get_remaining/)() const override | Hämtar antalet återstående tecken. |
| [GetNextChar](./getnextchar/)() override | Hämtar nästa tillgängliga tecken. |
| [MovePrevious](./moveprevious/)() override | Flyttar till föregående tecken. |
## Se även

* Class [EncoderFallbackBuffer](../encoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
