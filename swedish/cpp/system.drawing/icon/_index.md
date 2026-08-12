---
title: "System::Drawing::Icon-klass"
linktitle: "Ikon"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Icon-klass. Representerar en Windows-ikon. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.drawing/icon/
---
## Icon class


Representerar en [Windows](../../system.windows/)-ikon. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Icon : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Height](./get_height/)() const | Returnerar ikonens höjd. |
| [get_Width](./get_width/)() const | Returnerar ikonens bredd. |
| [Icon](./icon/)(const String\&) | Skapar en ny instans av [Icon](./)-klassen som representerar en ikon från den angivna filen. |
| [ToBitmap](./tobitmap/)() | Konverterar det aktuella objektet till ett [Bitmap](../bitmap/)-objekt. |
| virtual [~Icon](./~icon/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
