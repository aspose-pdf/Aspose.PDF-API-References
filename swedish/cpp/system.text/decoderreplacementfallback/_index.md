---
title: "System::Text::DecoderReplacementFallback klass"
linktitle: "DecoderReplacementFallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::DecoderReplacementFallback klass. Tillhandahåller en reservstrategi för att ersätta felaktig symbol med en platshållare. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.text/decoderreplacementfallback/
---
## DecoderReplacementFallback class


Tillhandahåller en reservstrategi för att ersätta felaktig symbol med en platshållare. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class DecoderReplacementFallback : public System::Text::DecoderFallback
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Skapar reservbuffer. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)() | Konstruktor som använder standard-\"?\"-ersättningssträng. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)(const String\&) | Konstruktor. |
| [get_DefaultString](./get_defaultstring/)() const | Hämtar ersättningssträng. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Hämtar maximalt antal tecken som instansen kan returnera. |
## Se även

* Class [DecoderFallback](../decoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
