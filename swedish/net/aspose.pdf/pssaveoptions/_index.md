---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsSaveOptions klass. Spara alternativ för export till PS PostScript eller EPS-format
type: docs
weight: 9740
url: /sv/net/aspose.pdf/pssaveoptions/
---
## PsSaveOptions klass

Spara alternativ för export till PS (PostScript) eller EPS-format.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | Konstruktör. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | Konstruktör. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller sätter ett booleanvärde som indikerar om teckensnittsglypher ska cachas medan aps-sidor förbereds. Förbättrar prestanda vid konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller sätter ett booleanvärde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | Hämtar/sätter en flagga som indikerar om teckensnitt måste bäddas in i det resulterande PS-dokumentet. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | Hämtar/sätter typ i vilken teckensnitt måste bäddas in i det resulterande PS-dokumentet. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Denna attribut aktiverar funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-sublager. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och sparaoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall sparaoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i flera trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera samma mönstrade bakgrundsbilder som placerats nära varandra. I sådana fall genererar renderare av målmformat (t.ex. MsWord för DOCS-format) ibland synliga gränser mellan delar av bakgrundsbilder, eftersom deras tekniker för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, vänligen försök använda denna inställning för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd denna alternativ endast när det verkligen är nödvändigt. |

### Se Även

* klass [UnifiedSaveOptions](../unifiedsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)