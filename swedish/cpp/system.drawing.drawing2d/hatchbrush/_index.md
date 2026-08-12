---
title: "System::Drawing::Drawing2D::HatchBrush class"
linktitle: "HatchBrush"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::HatchBrush class. Representerar en rektangulär pensel med ett streckningsmönster, en förgrundsfärg och en bakgrundsfärg. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.drawing.drawing2d/hatchbrush/
---
## HatchBrush class


Representerar en rektangulär pensel med en schablonstil, en förgrundsfärg och en bakgrundsfärg. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HatchBrush : public System::Drawing::Brush
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Skapar en exakt kopia av det aktuella objektet. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Returnerar ett värde som indikerar bakgrundsfärgen för denna pensel. |
| [get_ForegroundColor](./get_foregroundcolor/)() const | Returnerar ett värde som indikerar förgrundsfärgen för denna pensel. |
| [get_HatchStyle](./get_hatchstyle/)() const | Returnerar ett värde som indikerar schablonstilen för denna pensel. |
| [HatchBrush](./hatchbrush/)(HatchStyle, Color, Color) | RTTI-information. |
## Se även

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
