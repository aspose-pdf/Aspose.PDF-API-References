---
title: "Aspose::Pdf::MarkdownSaveOptions klass"
linktitle: "MarkdownSaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::MarkdownSaveOptions klass. Representerar dokumentets sparalternativklass i markdown-format i C++."
type: docs
weight: 10800
url: /sv/cpp/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class


Representerar dokumentets sparalternativklass i markdown-format.

```cpp
class MarkdownSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AreaToExtract](./get_areatoextract/)() const | Hämta eller ange ett rektangelområde för att extrahera innehåll till markdown. |
| [get_EmphasisStyle](./get_emphasisstyle/)() const | Hämtar stil för betoning för genererat dokument. |
| [get_ExtractVectorGraphics](./get_extractvectorgraphics/)() const | Hämtar och anger en egenskap som indikerar om vektorgrafik ska extraheras. |
| [get_HeadingLevels](./get_headinglevels/)() const | Definierar förväntade rubriknivåer att använda i FontSize-igenkänningsrubrikstrategi. Om detta egenskapsvärde är angivet, kommer rubrikigenkänning [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) strategi att väljas när [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../) strategier är inställda även om dokumentet innehåller bokmärken. |
| [get_HeadingRecognitionStrategy](./get_headingrecognitionstrategy/)() const | Hämtar rubrikigenkänningsstrategin. |
| [get_HeadingStyle](./get_headingstyle/)() const | Hämtar rubrikstilen för genererat dokument. |
| [get_LineBreakStyle](./get_linebreakstyle/)() const | Hämtar radbrytningsstilen för genererat dokument. |
| [get_ResourcesDirectoryName](./get_resourcesdirectoryname/)() const | Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Om värdet inte anges, kommer bilderna att skrivas till samma katalog som markdown-filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog kommer automatiskt att skapas i katalogen med den sparade markdown-filen. |
| [get_SubscriptAndSuperscriptConversion](./get_subscriptandsuperscriptconversion/)() const | Hämtar och anger tillåtelse att konvertera nedsänkt och upphöjt. Detta värde är sant som standard. |
| [get_UseImageHtmlTag](./get_useimagehtmltag/)() const | Hämtar och anger tillåtelse att använda en img-tagg för att infoga bilder till vänster och höger om texten. I detta fall kommer texten i markdown-visaren att flöda runt bilden. |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Skapar ett instansalternativ för att spara ett dokument i markdown-format. |
| [set_AreaToExtract](./set_areatoextract/)(const System::SharedPtr\<Rectangle\>\&) | Hämta eller ange ett rektangelområde för att extrahera innehåll till markdown. |
| [set_EmphasisStyle](./set_emphasisstyle/)(Aspose::Pdf::EmphasisStyle) | Anger stil för betoning för genererat dokument. |
| [set_ExtractVectorGraphics](./set_extractvectorgraphics/)(bool) | Hämtar och anger en egenskap som indikerar om vektorgrafik ska extraheras. |
| [set_HeadingLevels](./set_headinglevels/)(const System::SharedPtr\<Aspose::Pdf::HeadingLevels\>\&) | Definierar förväntade rubriknivåer att använda i FontSize-igenkänningsrubrikstrategi. Om detta egenskapsvärde är angivet, kommer rubrikigenkänning [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) strategi att väljas när [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../) strategier är inställda även om dokumentet innehåller bokmärken. |
| [set_HeadingRecognitionStrategy](./set_headingrecognitionstrategy/)(Aspose::Pdf::HeadingRecognitionStrategy) | Anger rubrikigenkänningsstrategin. |
| [set_HeadingStyle](./set_headingstyle/)(Aspose::Pdf::HeadingStyle) | Anger rubrikstilen för genererat dokument. |
| [set_LineBreakStyle](./set_linebreakstyle/)(Aspose::Pdf::LineBreakStyle) | Anger radbrytningsstilen för genererat dokument. |
| [set_ResourcesDirectoryName](./set_resourcesdirectoryname/)(const System::String\&) | Hämtar och anger katalognamnet för att spara dokumentresurser såsom bilder. Om värdet inte anges, kommer bilderna att skrivas till samma katalog som markdown-filen själv. Detta är inte en sökväg, det är bara ett namn! Denna katalog kommer automatiskt att skapas i katalogen med den sparade markdown-filen. |
| [set_SubscriptAndSuperscriptConversion](./set_subscriptandsuperscriptconversion/)(bool) | Hämtar och anger tillåtelse att konvertera nedsänkt och upphöjt. Detta värde är sant som standard. |
| [set_UseImageHtmlTag](./set_useimagehtmltag/)(bool) | Hämtar och anger tillåtelse att använda en img-tagg för att infoga bilder till vänster och höger om texten. I detta fall kommer texten i markdown-visaren att flöda runt bilden. |
## Se även

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
