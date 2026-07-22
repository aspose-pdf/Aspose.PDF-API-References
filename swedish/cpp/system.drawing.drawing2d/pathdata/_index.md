---
title: "System::Drawing::Drawing2D::PathData klass"
linktitle: "PathData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::PathData-klass. Innehåller de grafiska data som representerar en bana. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.drawing.drawing2d/pathdata/
---
## PathData class


Innehåller de grafiska data som representerar en bana. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class PathData : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Points](./get_points/)() | Returnerar en array som innehåller punkterna som utgör en bana. |
| [get_Types](./get_types/)() | Returnerar en array som innehåller värdena som specificerar typerna för motsvarande punkter i **Points**-arrayen. |
| [PathData](./pathdata/)() | Skapar ett tomt [PathData](./)-objekt. |
| [set_Points](./set_points/)(const ArrayPtr\<PointF\>\&) | Ställer in en array som innehåller punkterna som utgör en bana. |
| [set_Types](./set_types/)(const ArrayPtr\<uint8_t\>\&) | Ställer in en array som innehåller värdena som specificerar typerna för motsvarande punkter i **Points**-arrayen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
