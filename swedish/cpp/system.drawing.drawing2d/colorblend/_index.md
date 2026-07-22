---
title: "System::Drawing::Drawing2D::ColorBlend class"
linktitle: "ColorBlend"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::ColorBlend class. Innehåller arrayer av färger och positioner som används för att interpolera färgblandning i en flerfärgsgradient. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.drawing.drawing2d/colorblend/
---
## ColorBlend class


Innehåller arrayer av färger och positioner som används för att interpolera färgblandning i en flerfärgsgradient. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ColorBlend : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ColorBlend](./colorblend/)() | Skapar en ny instans av [ColorBlend](./)‑klassen. |
| [ColorBlend](./colorblend/)(int) | Skapar en ny instans av [Blend](../blend/)‑klassen. |
| [get_Colors](./get_colors/)() | Returnerar en array av färger att använda vid motsvarande positioner längs en gradient. |
| [get_Positions](./get_positions/)() | Returnerar arrayen med blandningspositioner längs en gradient. |
| [set_Colors](./set_colors/)(const ArrayPtr\<Color\>\&) | Ställer in en array av färger att använda vid motsvarande positioner längs en gradient. |
| [set_Positions](./set_positions/)(const ArrayPtr\<float\>\&) | Ställer in arrayen med blandningspositioner längs en gradient. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
