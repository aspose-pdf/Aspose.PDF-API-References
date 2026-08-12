---
title: "System::Drawing::ColorTranslator-klass"
linktitle: "ColorTranslator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::ColorTranslator-klass. Utför färgöversättningar. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.drawing/colortranslator/
---
## ColorTranslator class


Utför färgöversättningar. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ColorTranslator
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [FromHtml](./fromhtml/)(const System::String\&) | Konverterar den angivna HTML-färgrepresentationen till motsvarande [Color](../color/)-objekt. |
| static [FromWin32](./fromwin32/)(int) | Konverterar den angivna [Windows](../../system.windows/)-färgen till motsvarande [Color](../color/)-objekt. |
| static [ToHtml](./tohtml/)(const Color\&) | Konverterar det angivna [Color](../color/)-objektet till strängrepresentationen av motsvarande HTML-färg. |
## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
