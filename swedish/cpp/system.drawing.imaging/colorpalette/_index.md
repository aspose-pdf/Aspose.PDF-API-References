---
title: "System::Drawing::Imaging::ColorPalette klass"
linktitle: "ColorPalette"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::ColorPalette klass. Representerar en uppsättning 32-bitars ARGB-färger som utgör en färgpalett. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.drawing.imaging/colorpalette/
---
## ColorPalette class


Representerar en uppsättning 32-bitars ARGB-färger som utgör en färgpalett. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ColorPalette : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Entries](./get_entries/)() const | Returnerar en array av [Color](../../system.drawing/color/)-objekt som representeras av det aktuella objektet. |
| [get_Flags](./get_flags/)() const | Returnerar ett värde som specificerar hur färgvärdena i färgarrayen ska tolkas. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
