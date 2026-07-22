---
title: "Aspose::Pdf::Text::Font klass"
linktitle: "Typsnitt"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::Font klass. Representerar ett teckensnittobjekt i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.text/font/
---
## Font class


Representerar teckensnittobjekt.

```cpp
class Font : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CppIsSetTrailerable](./cppissettrailerable/)() |  |
| [get_BaseFont](./get_basefont/)() | Hämtar BaseFont-värdet för PDF-teckensnittobjektet. Även känt som teckensnittets PostScript-namn. |
| [get_DecodedFontName](./get_decodedfontname/)() | Ibland kan PDF-teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn. Detta namn är värdet för PDF-teckensnittsegenskapen "BaseFont" och ibland kan denna egenskap representeras i hexadecimal form. Om man läser detta namn direkt kan det visas i ett oläsligt format. För att få ett läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar det avkodade teckensnittsnamnet, så använd den i fall där du stöter på ett oläsligt [FontName](../). Om egenskapen [FontName](../) har ett läsbart format kommer denna egenskap att vara densamma som [FontName](../), så du kan använda den för alla fall där du behöver få teckensnittsnamnet i ett läsbart format. |
| [get_FontName](./get_fontname/)() const | Hämtar teckensnittets namn för [Font](./)-objektet. |
| [get_FontOptions](./get_fontoptions/)() | Användbara egenskaper för att finjustera [Font](./)-beteendet. |
| [get_IsAccessible](./get_isaccessible/)() const | Hämtar indikation på om teckensnittet finns (installerat) i systemet. |
| [get_IsEmbedded](./get_isembedded/)() const | Hämtar ett värde som indikerar om teckensnittet är inbäddat. [Font](./) baserat på IFont kommer automatiskt att bli delmängd och inbäddat. |
| [get_IsSubset](./get_issubset/)() | Hämtar ett värde som indikerar om teckensnittet är en delmängd. [Font](./) baserat på IFont kommer automatiskt att bli delmängd och inbäddat. |
| [GetLastFontEmbeddingError](./getlastfontembeddingerror/)() | Syftet med denna metod är att returnera en felbeskrivning om ett försök att inbädda teckensnittet misslyckades. Om det inte finns några felreturneras en tom sträng. |
| [MeasureString](./measurestring/)(const System::String\&, float) | Mäter strängen. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sparar teckensnittet i strömmen. [Note](../../aspose.pdf/note/) att teckensnittet sparas i ett intermediat TTF-format som endast är avsett att användas i en konverterad kopia av originaldokumentet. Teckensnittsfilen är inte avsedd att användas utanför originaldokumentets sammanhang. |
| [set_IsEmbedded](./set_isembedded/)(bool) | Ställer in ett värde som indikerar om teckensnittet är inbäddat. [Font](./) baserat på IFont kommer automatiskt att bli delmängd och inbäddat. |
| [set_IsSubset](./set_issubset/)(bool) | Ställer in ett värde som indikerar om teckensnittet är en delmängd. [Font](./) baserat på IFont kommer automatiskt att bli delmängd och inbäddat. |



## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
