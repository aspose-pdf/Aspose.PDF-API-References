---
title: "System::Drawing::Drawing2D::Blend klass"
linktitle: "Blend"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::Blend klass. Representerar ett blandningsmönster för ett LinearGradientBrush-objekt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.drawing.drawing2d/blend/
---
## Blend class


Representerar ett blandningsmönster för ett [LinearGradientBrush](../lineargradientbrush/) objekt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Blend : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Blend](./blend/)() | Skapar en ny instans av [Blend](./) klass. |
| [Blend](./blend/)(int) | Skapar en ny instans av [Blend](./) klass. |
| [get_Factors](./get_factors/)() const | Returnerar arrayen med blandningsfaktorer för gradienten. |
| [get_Positions](./get_positions/)() const | Returnerar arrayen med blandningspositioner för gradienten. |
| [set_Factors](./set_factors/)(const ArrayPtr\<float\>\&) | Ställer in arrayen med blandningsfaktorer för gradienten. |
| [set_Positions](./set_positions/)(const ArrayPtr\<float\>\&) | Ställer in arrayen med blandningspositioner för gradienten. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
