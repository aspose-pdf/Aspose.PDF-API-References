---
title: "System::Drawing::Imaging::FrameDimension klass"
linktitle: "FrameDimension"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::FrameDimension-klass. Tillhandahåller egenskaper som hämtar bildens ramdimensioner. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.drawing.imaging/framedimension/
---
## FrameDimension class


Tillhandahåller egenskaper som hämtar bildens ramdimensioner. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class FrameDimension : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(FrameDimensionPtr) | Avgör om det angivna [FrameDimension](./)-objektet är ekvivalent med det aktuella objektet. |
| [FrameDimension](./framedimension/)(const System::Guid\&) | Skapar ett nytt [FrameDimension](./)-objekt och initierar det med det angivna GUID:et. |
| [get_Guid](./get_guid/)() const | Returnerar GUID som är associerat med det aktuella objektet. |
| static [get_Page](./get_page/)() | Returnerar sidans dimension. |
| static [get_Resolution](./get_resolution/)() | Returnerar upplösningens dimension. |
| static [get_Time](./get_time/)() | Returnerar tidsdimensionen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
