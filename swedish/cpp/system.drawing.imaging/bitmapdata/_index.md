---
title: "System::Drawing::Imaging::BitmapData-klass"
linktitle: "BitmapData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::BitmapData-klass. Representerar en uppsättning attribut för en bitmap-bild. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.drawing.imaging/bitmapdata/
---
## BitmapData class


Representerar en uppsättning attribut för en bitmap-bild. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class BitmapData : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Height](./get_height/)() const | Returnerar bildens höjd i pixlar. |
| [get_PixelFormat](./get_pixelformat/)() const | Returnerar pixelformatet för bitmap-bilden. |
| [get_Scan0](./get_scan0/)() const | Returnerar adressen till den första pixeldata i bitmapen. |
| [get_Stride](./get_stride/)() const | Returnerar radstegets bredd för bilden i byte. |
| [get_Width](./get_width/)() const | Returnerar bildens bredd i pixlar. |
| [set_Height](./set_height/)(int) | Ställer in bildens höjd i pixlar. |
| [set_PixelFormat](./set_pixelformat/)(PixelFormat) | Ställer in pixelformatet för bitmap-bilden. |
| [set_Scan0](./set_scan0/)(IntPtr) | Ställer in adressen till den första pixeldata i bitmapen. |
| [set_Stride](./set_stride/)(int) | Ställer in radstegets bredd för bilden i byte. |
| [set_Width](./set_width/)(int) | Ställer in bildens bredd i pixlar. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
