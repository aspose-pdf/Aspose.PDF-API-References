---
title: "System::Drawing::Text::PrivateFontCollection klass"
linktitle: "PrivateFontCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Text::PrivateFontCollection klass. Representerar en samling av teckensnittsfamiljer som tillhandahålls av klientapplikationen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.drawing.text/privatefontcollection/
---
## PrivateFontCollection class


Representerar en samling av teckensnittsfamiljer som tillhandahålls av klientapplikationen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class PrivateFontCollection : public System::Drawing::Text::FontCollection
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddFont](./addfont/)(const System::ArrayPtr\<uint8_t\>\&, int) | Lägger till det angivna teckensnittet i samlingen. |
| [AddFontFile](./addfontfile/)(const String\&) | Lägger till ett teckensnitt från den angivna filen i samlingen. |
| [get_Families](./get_families/)() override | Returnerar en array av [FontFamily](../../system.drawing/fontfamily/)-objekt som är associerade med teckensnittssamlingen som representeras av det aktuella objektet. |
## Se även

* Class [FontCollection](../fontcollection/)
* Namespace [System::Drawing::Text](../)
* Library [Aspose.PDF for C++](../../)
