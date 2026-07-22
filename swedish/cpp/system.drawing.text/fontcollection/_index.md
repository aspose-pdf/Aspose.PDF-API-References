---
title: "System::Drawing::Text::FontCollection-klass"
linktitle: "FontCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Text::FontCollection-klass. En basklass för installerade och privata teckensnittssamlingar. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.drawing.text/fontcollection/
---
## FontCollection class


En basklass för installerade och privata teckensnittssamlingar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FontCollection : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Frigör operativsystemets resurser som erhållits av det aktuella objektet. |
| virtual [get_Families](./get_families/)() | Returnerar en array av [FontFamily](../../system.drawing/fontfamily/)-objekt som är associerade med teckensnittssamlingen som representeras av det aktuella objektet. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing::Text](../)
* Library [Aspose.PDF for C++](../../)
