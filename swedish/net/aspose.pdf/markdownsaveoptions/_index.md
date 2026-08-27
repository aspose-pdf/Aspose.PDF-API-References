---
title: "Klass MarkdownSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.MarkdownSaveOptions-klass. Representerar dokumentets sparalternativklass i markdown-format"
type: docs
weight: 7050
url: /sv/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

Representerar dokumentets sparalternativsklass i markdown-format.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Hämta eller ange ett rektangelområde för att extrahera innehåll till markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Hämtar eller anger stil för betoning i det genererade dokumentet. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF‑dokument med OCR‑undervärld. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Hämtar och anger en egenskap som indikerar om vektorgrafik ska extraheras. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Definierar förväntade rubriknivåer som ska användas i FontSize‑igenkänning av rubrikstrategi. Om detta egenskapsvärde är satt, kommer heuristisk rubrikigenkänningsstrategi att väljas när !:PdfToMarkdown.HeadingRecognitionStrategy.Auto‑strategier är satta även om dokumentet innehåller bokmärken. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Hämtar eller anger rubrikigenkänningsstrategin. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Hämtar eller anger rubrikstilen för genererat Document. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Hämtar eller anger radbrytningsstilen för genererat Document. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Hämtar och anger katalognamnet för att spara Document‑resurser såsom bilder. Om värdet inte anges, kommer bilderna att skrivas till samma katalog som markdown‑filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog kommer automatiskt att skapas i katalogen med den sparade markdown‑filen. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Hämtar och anger tillåtelse att konvertera nedsänkt och upphöjd text. Detta värde är sant som standard. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Hämtar och anger tillåtelse att använda en img‑tagg för att infoga bilder till vänster och höger om texten. I så fall kommer texten i markdown‑visaren att flöda runt bilden. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i några trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF‑filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS‑format) ibland generera synliga gränser mellan delar av bakgrundsbilder, eftersom deras teknik för kantutjämning (anti‑aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

### Se även

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


