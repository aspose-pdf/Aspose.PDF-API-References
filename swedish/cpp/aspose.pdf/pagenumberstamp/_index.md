---
title: "Aspose::Pdf::PageNumberStamp class"
linktitle: "PageNumberStamp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageNumberStamp class. Representerar sidnummerstämpel och används för att numrera sidor i C++."
type: docs
weight: 14200
url: /sv/cpp/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class


Representerar sidnummerstämpel och används för att numrera sidor.

```cpp
class PageNumberStamp : public Aspose::Pdf::TextStamp
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Format](./get_format/)() const | Strängvärde för stämpling av sidnummer. Värdet måste innehålla tecknet '#' som ersätts med sidnumret under stämplingsprocessen. |
| [get_NumberingStyle](./get_numberingstyle/)() const | Numreringsstil som används av denna stämpel. |
| [get_StartingNumber](./get_startingnumber/)() const | Hämtar värdet för startsidans nummer. Övriga sidor kommer att numreras med början från detta värde. |
| [PageNumberStamp](./pagenumberstamp/)(const System::String\&) | Initierar en ny instans av klassen [PageNumberStamp](./). |
| [PageNumberStamp](./pagenumberstamp/)() | Initierar en ny instans av klassen [PageNumberStamp](./). Formatet är satt till "#". |
| [PageNumberStamp](./pagenumberstamp/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Skapar [PageNumberStamp](./) med formaterad text. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Lägger till sidnummer. |
| [set_Format](./set_format/)(const System::String\&) | Strängvärde för stämpling av sidnummer. Värdet måste innehålla tecknet '#' som ersätts med sidnumret under stämplingsprocessen. |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Numreringsstil som används av denna stämpel. |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Ställer in värdet för startsidans nummer. Övriga sidor kommer att numreras med början från detta värde. |
## Se även

* Class [TextStamp](../textstamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
