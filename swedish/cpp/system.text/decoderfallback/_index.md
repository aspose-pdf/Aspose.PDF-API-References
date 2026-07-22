---
title: "System::Text::DecoderFallback‑klassen"
linktitle: "DecoderFallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::DecoderFallback‑klassen. Tillhandahåller ett fallback‑API för att hantera avkodningsfel. Objekt av denna klass bör endast allokeras med funktionen `System::MakeObject()` . Skapa aldrig en instans av denna typ på stacken eller med operatorn `new`, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en `System::SmartPtr`‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.text/decoderfallback/
---
## DecoderFallback class


Tillhandahåller ett fallback‑API för att hantera avkodningsfel. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn `new`, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class DecoderFallback : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CreateFallbackBuffer](./createfallbackbuffer/)() | Hämtar bufferten som är associerad med fallback‑algoritmen. |
| static [get_ExceptionFallback](./get_exceptionfallback/)() | Hämtar standardimplementationen för undantags‑fallback. |
| virtual [get_MaxCharCount](./get_maxcharcount/)() const | Hämtar maximalt antal tecken som kan returneras av fallback. |
| static [get_ReplacementFallback](./get_replacementfallback/)() | Hämtar standardimplementeringen för ersättnings‑fallback. |
| static [get_StandardSafeFallback](./get_standardsafefallback/)() | Hämtar standardimplementationen för säker standard‑fallback. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
