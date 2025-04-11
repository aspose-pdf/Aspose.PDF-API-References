---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MarkdownSaveOptions klass. Representerar dokumentets spara alternativklass i markdown-format
type: docs
weight: 6910
url: /sv/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions klass

Representerar dokumentets spara alternativklass i markdown-format.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Den standardkonstruktor. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Hämta eller ställ in ett rektangulärt område för att extrahera innehåll till markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller ställer in ett boolean-värde som indikerar om teckensnittsglyphs ska cachas medan aps-sidor förbereds. Förbättrar prestanda vid konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller ställer in ett boolean-värde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Hämtar eller ställer in stilen för betoning för det genererade dokumentet. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Denna attribut aktiverar funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-sublager. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Hämtar och ställer in en egenskap som indikerar om vektorgrafik ska extraheras. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Definierar förväntade rubriknivåer att använda i strategin för igenkänning av rubriker i FontSize. Om detta egenskapsvärde är inställt, kommer rubrikigenkänning !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic strategin att väljas när !:PdfToMarkdown.HeadingRecognitionStrategy.Auto strategier är inställda även om dokumentet innehåller bokmärken. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Hämtar eller ställer in strategin för rubrikigenkänning. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Hämtar eller ställer in rubrikstilen för det genererade dokumentet. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Hämtar eller ställer in radbrytningstilen för det genererade dokumentet. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Hämtar och ställer in katalognamnet för att spara dokumentresurser som bilder. Om värdet inte anges, kommer bilderna att skrivas till samma katalog som markdown-filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog kommer automatiskt att skapas i katalogen med den sparade markdown-filen. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Hämtar och ställer in tillåtelse att konvertera nedsänkta och upphöjda tecken. Detta värde är sant som standard. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Hämtar och ställer in tillåtelse att använda en img-tagg för att infoga bilder till vänster och höger om texten. I detta fall kommer texten i markdown-visaren att omge bilden. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-objekt som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och sparaoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall sparaoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i flera trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera samma mönstrade bakgrundsbilder som placerats nära varandra. I sådana fall genererar renderare av målformat (t.ex. MsWord för DOCS-format) ibland synliga gränser mellan delar av bakgrundsbilder, eftersom deras tekniker för att mjuka upp bildkanter (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, vänligen försök att använda denna inställning för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd denna alternativ endast när det verkligen är nödvändigt. |

### Se Även

* klass [UnifiedSaveOptions](../unifiedsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)