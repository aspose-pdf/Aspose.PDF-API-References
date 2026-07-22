---
title: "System::Text::EncoderExceptionFallback klass"
linktitle: "EncoderExceptionFallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncoderExceptionFallback-klass. Tillhandahåller en fallback‑strategi som kastar undantag. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.text/encoderexceptionfallback/
---
## EncoderExceptionFallback class


Tillhandahåller en undantagskastande reservstrategi. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class EncoderExceptionFallback : public System::Text::EncoderFallback
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Skapar reservbuffer. |
| [EncoderExceptionFallback](./encoderexceptionfallback/)() | Konstruktor. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Hämtar maximalt antal tecken som instansen kan returnera. |
## Se även

* Class [EncoderFallback](../encoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
