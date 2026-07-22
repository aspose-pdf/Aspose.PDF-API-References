---
title: "System::Drawing::Drawing2D::RegionData class"
linktitle: "RegionData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::RegionData class. Innehåller data som definierar en region. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd den pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system.drawing.drawing2d/regiondata/
---
## RegionData class


Innehåller data som definierar en region. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class RegionData : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Data](./get_data/)() | Returnerar en bytearray som innehåller data som definierar en region. |
| [RegionData](./regiondata/)(const ArrayPtr\<uint8_t\>\&) | Skapar en ny instans av [RegionData](./)-klassen och initierar den med de angivna data. |
| [set_Data](./set_data/)(const ArrayPtr\<uint8_t\>\&) | Ställer in regiondata för det aktuella objektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
