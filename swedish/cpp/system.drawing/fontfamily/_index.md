---
title: "System::Drawing::FontFamily-klass"
linktitle: "FontFamily"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::FontFamily-klass. Representerar en grupp av typsnitt som delar en liknande grunddesign. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.drawing/fontfamily/
---
## FontFamily class


Representerar en grupp av typsnitt som delar en liknande grunddesign. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FontFamily : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() | Returnerar en kopia av det aktuella [FontFamily](./)-objektet. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Avgör om det aktuella och det angivna objektet är identiska. |
| [FontFamily](./fontfamily/)(const String\&) | Skapar en ny instans av [FontFamily](./)-klassen som representerar en teckensnittsfamilj med det angivna namnet. |
| [FontFamily](./fontfamily/)(const String\&, const SharedPtr\<Text::FontCollection\>\&) | Skapar en ny instans av [FontFamily](./) i den angivna FontCollection med det angivna namnet. |
| [FontFamily](./fontfamily/)(Text::GenericFontFamilies) | Skapar en ny instans av [FontFamily](./) från den angivna generiska teckensnittsfamiljen. |
| static [get_Families](./get_families/)() | Returnerar en array som innehåller alla [FontFamily](./)-objekt som är associerade med det aktuella grafik‑kontextet. |
| static [get_GenericMonospace](./get_genericmonospace/)() | Returnerar ett [FontFamily](./)-objekt som representerar en generisk monospaced teckensnittsfamilj. |
| static [get_GenericSansSerif](./get_genericsansserif/)() | Returnerar ett [FontFamily](./)-objekt som representerar en generisk sans‑serif teckensnittsfamilj. |
| static [get_GenericSerif](./get_genericserif/)() | Returnerar ett [FontFamily](./)-objekt som representerar en generisk serif teckensnittsfamilj. |
| [get_Name](./get_name/)() const | Returnerar namnet på teckensnittsfamiljen som representeras av det aktuella objektet. |
| [GetCellAscent](./getcellascent/)(FontStyle) | Returnerar cellens höjning för teckensnittsfamiljen som representeras av det aktuella objektet för den angivna teckensnittsstilen. |
| [GetCellDescent](./getcelldescent/)(FontStyle) | Returnerar cellens sänkning för teckensnittsfamiljen som representeras av det aktuella objektet för den angivna teckensnittsstilen. |
| [GetEmHeight](./getemheight/)(FontStyle) | Returnerar höjden på em‑kvadraten i teckensnittets designenheter för den angivna stilen. |
| [GetLineSpacing](./getlinespacing/)(FontStyle) | Returnerar radavståndet för teckensnittsfamiljen som representeras av det aktuella objektet för den angivna teckensnittsstilen. |
| [GetName](./getname/)(int) const | Returnerar namnet på teckensnittsfamiljen som representeras av det aktuella objektet. |
| [IsStyleAvailable](./isstyleavailable/)(FontStyle) | Avgör om den angivna teckensnittsstilen är tillgänglig. |
| virtual [~FontFamily](./~fontfamily/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
