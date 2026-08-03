---
title: "Klass PdfFormatConversionOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PdfFormatConversionOptions-klass. representerar en uppsättning alternativ för att konvertera PDF-dokument."
type: docs
weight: 8520
url: /sv/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

representerar en uppsättning alternativ för att konvertera PDF-dokument.

```csharp
public class PdfFormatConversionOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Hämtar PdfFormatConversionOptions-objekt med standardparametrar. |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Denna flagga styr textjustering i det konverterade dokumentet. Som standard påverkar dokumentkonvertering inte textjustering och lämnar texten oförändrad. Men i vissa fall kan teckensnittssubstitution orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När denna flagga är satt kommer speciella justeringsoperationer att utföras. Flaggan bör endast sättas för dokument som har problem med överlappande text eller extra mellanslag, eftersom användning av flaggan minskar prestanda och i vissa fall kan förstöra textinnehållet. |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | Hämtar eller anger inställningarna för automatisk taggning under PDF-formatkonvertering. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Åtgärd för bilder med mjuk mask. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Åtgärd för objekt som inte kan konverteras. |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. Denna parameter har endast betydelse när flaggan [`OptimizeFileSize`](./optimizefilesize/) är satt till true. Som standard används kombinationen av strategierna SubsetFonts och RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Alternativ för fall då det inte är möjligt att bädda in vissa teckensnitt i PDF-dokumentet. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF-format. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Hämtar eller anger filnamnet för icc-profilen. Om null används standard-ICC-profilen. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Hämtar/anger körning av bildströmmar i asynkront läge. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Är läge för lågminneskonvertering aktiverat. |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Hämtar eller anger om data ska överföras från Info till Metadata vid konvertering till PDF 2.0. True som standard. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Sökväg till fil där kommentarer kommer att lagras. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Ström där kommentarer kommer att lagras. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Innehåller flaggor för att styra PDF/A-konverteringsprocessen för fall då källdokumentet inte motsvarar PDF/A-specifikationen. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Denna egenskap är en ut-egenskap. Den innehåller alla teckensnitt (teckensnittsnamn) som inte hittades på datorn vid den senaste PDF/A-konverteringen. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Hämtar eller anger en flagga som aktiverar/inaktiverar speciellt konverteringsläge för att skapa PDF/A-dokument med reducerad filstorlek. För närvarande påverkar denna flagga optimeringen av teckensnitt som används i PDF-dokumentet, och eventuellt kommer flaggan i framtiden även att användas för att slå på optimering av andra datastrukturer, såsom grafik. Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt kan den avsevärt minska konverteringsprestandan. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Hämtar eller anger [`OutputIntent`](../outputintent/) för PDF-formatkonverteringen. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Strategi för att bearbeta symboler från Unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Strategi för att kopiera kodningsdata för symboliska teckensnitt om ett symboliskt TrueType font har mer än en kodningstabell. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Åtgärd för bildmaskerade objekt |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Regler för att lösa problem med unicode‑mappning. Kan vara null. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Strategi för att justera text. Denna parameter har mening endast när flaggan [`AlignText`](./aligntext/) är satt till true. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


