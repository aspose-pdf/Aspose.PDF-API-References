---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptions klass. representerar en uppsättning alternativ för att konvertera PDF-dokument
type: docs
weight: 8380
url: /sv/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions klass

representerar en uppsättning alternativ för att konvertera PDF-dokument

```csharp
public class PdfFormatConversionOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konstruktör |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Hämtar PdfFormatConversionOptions-objekt med standardparametrar |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Denna flagga kontrollerar textjustering i det konverterade dokumentet. Som standard påverkar dokumentkonvertering inte textjusteringen och lämnar texten som den är. Men i vissa fall orsakar teckensubstitution textöverlappar eller extra utrymmen i det konverterade dokumentet. När denna flagga är inställd kommer speciella justeringsoperationer att utföras. Denna flagga bör endast ställas in för dokument som har problem med överlappande text eller extra textutrymmen eftersom användningen av denna flagga minskar prestanda och i vissa fall kan förstöra textinnehållet. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Åtgärd för bilder med mjuk mask. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Åtgärd för objekt som inte kan konverteras |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Strategi(er) för att utesluta överflödiga typsnitt och minska dokumentfilstorleken. Denna parameter har mening endast när flaggan [`OptimizeFileSize`](./optimizefilesize/) är inställd på true. Som standard används en kombination av strategierna SubsetFonts och RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Alternativ för fall när det inte är möjligt att bädda in vissa typsnitt i PDF-dokumentet. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF-format. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Hämtar eller ställer in filnamnet för icc-profilnamnet. Vid null används standardicc-profilen. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Hämtar/ställer in körning av bildströmmar i asynkront läge. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Är lågt minneskonverteringsläge aktiverat |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Hämtar eller ställer in om data från Info ska överföras till Metadata när det konverteras till PDF 2.0. Sant som standard. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Sökväg till fil där kommentarer kommer att lagras. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Ström där kommentarer kommer att lagras. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Håller flaggor för att kontrollera PDF/A-konverteringsprocessen för fall när källdokumentet inte överensstämmer med PDF/A-specifikationen. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Denna egenskap är en ut-egenskap. Den håller alla typsnitt (typsnittnamn) som inte hittades på datorn vid den senaste PDF/A-konverteringen. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Hämtar eller ställer in en flagga som aktiverar/inaktiverar speciellt konverteringsläge för att få PDF/A-dokument med minskad filstorlek. Nu påverkar denna flagga optimeringen av typsnitt som används i PDF-dokumentet, eventuellt kommer denna flagga också att användas för att slå på optimering för andra datastrukturer, såsom grafik. Sättningen av denna flagga och läget kan avsevärt minska filstorleken men samtidigt kan det avsevärt minska konverteringsprestanda. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Hämtar eller ställer in [`OutputIntent`](../outputintent/) för PDF-formatkonvertering. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Strategi för att bearbeta symboler från unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Strategi för att kopiera kodningsdata för symboliska typsnitt om symboliskt TrueType-typsnitt har mer än en kodningssubtabell. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Åtgärd för bildmaskerade objekt |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Regler för att lösa problem med unicode-mappning. Kan vara null. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Strategi för att justera text. Denna parameter har mening endast när flaggan [`AlignText`](./aligntext/) är inställd på true. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)