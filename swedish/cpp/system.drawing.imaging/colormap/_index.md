---
title: "System::Drawing::Imaging::ColorMap klass"
linktitle: "ColorMap"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::ColorMap-klass. Representerar en karta för att konvertera färger. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.drawing.imaging/colormap/
---
## ColorMap class


Representerar en karta för att konvertera färger. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ColorMap : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_NewColor](./get_newcolor/)() const | Returnerar det nya [Color](../../system.drawing/color/)‑objektet som representerar färgen att konvertera till. |
| [get_OldColor](./get_oldcolor/)() const | Returnerar det gamla [Color](../../system.drawing/color/)‑objektet som representerar färgen som ska konverteras. |
| [set_NewColor](./set_newcolor/)(const Color\&) | Sätter det nya [Color](../../system.drawing/color/)‑objektet som representerar färgen att konvertera till. |
| [set_OldColor](./set_oldcolor/)(const Color\&) | Sätter det gamla [Color](../../system.drawing/color/)‑objektet som representerar färgen som ska konverteras. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
