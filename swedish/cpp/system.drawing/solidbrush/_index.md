---
title: "System::Drawing::SolidBrush-klass"
linktitle: "SolidBrush"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::SolidBrush-klass. Representerar en enkelfärgad pensel. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2400
url: /sv/cpp/system.drawing/solidbrush/
---
## SolidBrush class


Representerar en enkelfärgad pensel. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SolidBrush : public System::Drawing::Brush
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet. |
| [get_Color](./get_color/)() const | Returnerar denna pensels färg. |
| [set_Color](./set_color/)(Color) | Ställer in färgen på denna pensel. |
| [SolidBrush](./solidbrush/)(const Color\&) | Skapar ett nytt [SolidBrush](./)-objekt och initierar det med den angivna färgen. |
## Se även

* Class [Brush](../brush/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
