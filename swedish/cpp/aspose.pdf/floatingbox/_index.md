---
title: "Aspose::Pdf::FloatingBox-klass"
linktitle: "FloatingBox"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::FloatingBox-klass. Representerar en FloatingBox i ett Pdf-dokument. FloatingBox är anpassat placerad i C++."
type: docs
weight: 5700
url: /sv/cpp/aspose.pdf/floatingbox/
---
## FloatingBox class


Representerar en [FloatingBox](./) i ett [Pdf](../)-dokument. [FloatingBox](./) är anpassat placerad.

```cpp
class FloatingBox : public Aspose::Pdf::BaseParagraph
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klonar ett nytt [FloatingBox](./)-objekt. [Paragraphs](../paragraphs/) i den flytande rutan klonas inte. |
| [FloatingBox](./floatingbox/)(float, float) | Initierar en ny instans av klassen [FloatingBox](./) med angiven bredd och höjd. |
| [FloatingBox](./floatingbox/)() | Initierar en ny instans av klassen [FloatingBox](./). |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Hämtar ett [Aspose::Pdf::Color](../color/)-objekt som anger bakgrundsfärgen för den flytande rutan. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Hämtar bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokumentet). |
| [get_Border](./get_border/)() const | Hämtar ett [BorderInfo](../borderinfo/)-objekt som anger kantinformation för den flytande rutan. |
| [get_ColumnInfo](./get_columninfo/)() const | Hämtar kolumninformation. |
| [get_Height](./get_height/)() const | Hämtar ett flyttal som anger höjden på den flytande rutan. |
| [get_IsNeedRepeating](./get_isneedrepeating/)() const | Hämtar ett booleskt värde som anger om stycket ska upprepas på nästa sida. Standardvärdet är false. Attributet är endast giltigt när själva stycket och objektet som dess ReferenceParagraphID refererar till båda ingår i RepeatingRows. |
| [get_Left](./get_left/)() const | Hämtar tabellens vänstra koordinat. |
| [get_Padding](./get_padding/)() const | Hämtar ett [MarginInfo](../margininfo/)-objekt som anger utfyllnaden för den flytande rutan. |
| [get_Paragraphs](./get_paragraphs/)() const | Hämtar en [Paragraphs](../paragraphs/)-samling som visar alla stycken i cellen. |
| [get_PositioningMode](./get_positioningmode/)() const | Anger variant för att bestämma placeringen av [FloatingBox](./) på sidan. |
| [get_Top](./get_top/)() const | Hämtar tabellens övre koordinat. |
| [get_Width](./get_width/)() const | Hämtar ett flyttal som anger bredden på den flytande rutan. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Ställer in ett [Aspose::Pdf::Color](../color/)-objekt som anger bakgrundsfärgen för den flytande rutan. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Image\>\&) | Ställer in bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokumentet). |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Ställer in ett [BorderInfo](../borderinfo/)-objekt som anger kantinformationen för den flytande rutan. |
| [set_ColumnInfo](./set_columninfo/)(const System::SharedPtr\<Aspose::Pdf::ColumnInfo\>\&) | Ställer in kolumninformation. |
| [set_Height](./set_height/)(double) | Ställer in ett flyttal som anger höjden på den flytande rutan. |
| [set_IsNeedRepeating](./set_isneedrepeating/)(bool) | Ställer in ett booleskt värde som anger om stycket ska upprepas på nästa sida. Standardvärdet är false. Attributet är endast giltigt när själva stycket och objektet som dess ReferenceParagraphID refererar till båda ingår i RepeatingRows. |
| [set_Left](./set_left/)(double) | Ställer in tabellens vänstra koordinat. |
| [set_Padding](./set_padding/)(const System::SharedPtr\<MarginInfo\>\&) | Ställer in ett [MarginInfo](../margininfo/)‑objekt som anger utfyllnaden för den flytande rutan. |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Ställer in en [Paragraphs](../paragraphs/)‑samling som anger alla stycken i cellen. |
| [set_PositioningMode](./set_positioningmode/)(ParagraphPositioningMode) | Anger variant för att bestämma placeringen av [FloatingBox](./) på sidan. |
| [set_Top](./set_top/)(double) | Ställer in tabellens övre koordinat. |
| [set_Width](./set_width/)(double) | Ställer in ett flyttal som anger bredden på den flytande rutan. |
## Se även

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
