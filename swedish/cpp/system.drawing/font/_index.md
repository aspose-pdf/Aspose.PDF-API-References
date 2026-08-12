---
title: "System::Drawing::Font-klass"
linktitle: "Typsnitt"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Font-klass. Representerar ett specifikt format för text, inklusive teckensnitt, storlek och stil. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.drawing/font/
---
## Font class


Representerar ett specifikt format för text, inklusive teckensnitt, storlek och stil. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Font : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() | Returnerar en kopia av det aktuella typsnittet. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Avgör om det aktuella och det angivna objektet är identiska. |
| [Font](./font/)(const SharedPtr\<Font\>\&, FontStyle) | Skapar en ny instans av [Font](./)-klassen som representerar det angivna befintliga typsnittet med den angivna typsnittsstilen. |
| [Font](./font/)(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) | Skapar en ny instans av [Font](./)-klassen. |
| [Font](./font/)(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) | Skapar en ny instans av [Font](./)-klassen. |
| [Font](./font/)(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) | Skapar en ny instans av [Font](./)-klassen. |
| [Font](./font/)(const String\&, float, GraphicsUnit) | Skapar en ny instans av [Font](./)-klassen. |
| static [FromLogFont](./fromlogfont/)(const SharedPtr\<Object\>\&) | INTE IMPLEMENTERAD. |
| [get_Bold](./get_bold/)() | Avgör om typsnittet som representeras av det aktuella objektet har den fetstilta stilen tillämpad. |
| [get_FontFamily](./get_fontfamily/)() | Returnerar typsnittsfamiljen för typsnittet som representeras av det aktuella objektet. |
| [get_FontStyle](./get_fontstyle/)() | Returnerar teckensnittsstilen för teckensnittet som representeras av det aktuella objektet. |
| [get_GdiCharSet](./get_gdicharset/)() | Returnerar ett värde som indikerar den GDI-teckenuppsättning som används av teckensnittet som representeras av det aktuella objektet. |
| [get_Height](./get_height/)() | Returnerar radavståndet för teckensnittet som representeras av det aktuella objektet i pixlar. |
| [get_Italic](./get_italic/)() | Bestämmer om teckensnittet som representeras av det aktuella objektet har den kursiva stilen tillämpad. |
| [get_Name](./get_name/)() | Returnerar teckensnittets namn för teckensnittet som representeras av det aktuella objektet. |
| [get_OriginalFontName](./get_originalfontname/)() | Returnerar det ursprungligen angivna namnet på teckensnittet. |
| [get_Size](./get_size/)() | Returnerar em-storleken för teckensnittet som representeras av det aktuella objektet, mätt i de enheter som anges av egenskapen Unit. |
| [get_SizeInPoints](./get_sizeinpoints/)() | Returnerar em-storleken för teckensnittet som representeras av det aktuella objektet i punkter. |
| [get_Strikeout](./get_strikeout/)() | Bestämmer om teckensnittet som representeras av det aktuella objektet har genomstruken stil tillämpad. |
| [get_Style](./get_style/)() | Returnerar teckensnittsstilen för teckensnittet som representeras av det aktuella objektet. |
| [get_Underline](./get_underline/)() | Bestämmer om teckensnittet som representeras av det aktuella objektet har understruken stil tillämpad. |
| [get_Unit](./get_unit/)() | Returnerar mätenheten för teckensnittet som representeras av det aktuella objektet. |
| [GetHeight](./getheight/)(const SharedPtr\<Graphics\>\&) | Returnerar radavståndet för teckensnittet som representeras av det aktuella objektet, i den aktuella enheten för ett specificerat [Graphics](../graphics/)‑objekt. |
| [GetHeight](./getheight/)(float) | Returnerar höjden på teckensnittet som representeras av det aktuella objektet när det ritas på en displayenhet med den specificerade vertikala upplösningen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
