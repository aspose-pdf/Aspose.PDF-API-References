---
title: PdfFormatConversionOptions
second_title: Aspose.PDF för .NET API Referens
description: representerar en uppsättning alternativ för att konvertera PDF-dokument
type: docs
weight: 6030
url: /sv/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

representerar en uppsättning alternativ för att konvertera PDF-dokument

```csharp
public class PdfFormatConversionOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | Konstruktör |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konstruktör |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | Hämtar PdfFormatConversionOptions-objekt med standardparametrar |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | Denna flagga kontrollerar textjustering i konverterade dokument. Som standard påverkar dokumentkonvertering inte textjustering och lämnar texten som den är. Men i vissa fall orsakar font substitution textöverlappning eller extra mellanslag i konverterade dokument. När denna flagga är set kommer speciella inriktningsoperationer att utföras. Den här flaggan bör endast ställas in för documents som har problem med överlappande text eller extra textmellanslag som orsakar användningen av denna flagga reduce prestanda och i vissa fall kan skada textinnehållet. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | Action för bilder med mjuk mask. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | Åtgärd för objekt som inte kan konverteras |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentfilstorleken. Den här parametern har känsla endast när flagga[`OptimizeFileSize`](./optimizefilesize) är satt till true. Som standardkombination av strategierSubsetFonts och RemoveDuplicatedFonts används. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | Alternativ för fall då det inte är möjligt att bädda in vissa typsnitt i PDF-dokument. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | PDF-format. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | Hämtar eller ställer in filnamnet för icc-profilnamnet. I fallet med null används standard-icc-profilen. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | Får/ställer in körning av bildströmmar i asynkront läge. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | Är konverteringsläge för lågt minne aktiverat |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | Hämtar eller ställer in om data ska skickas från Info till Metadata när den konverteras till PDF 2.0. True som standard. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | Sökväg till fil där kommentarer kommer att lagras. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | Streama där kommentarer kommer att lagras. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | Innehåller flaggor för att styra PDF/A-konverteringsprocessen i fall då källdokument inte motsvarar PDF/A-specifikationen. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | Den här egenskapen är en egendom. Den innehåller alla typsnitt (typsnittsnamn) som inte hittades på datorn vid senaste PDF/A-konvertering. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | Hämtar eller ställer in en flagga som aktiverar/inaktiverar speciellt konverteringsläge för att hämta PDF/A-dokument med minskad filstorlek. Nu påverkar denna flagga optimering av teckensnitt som används i PDF-dokument, i framtiden kommer kanske även denna flagga att användas för att slå på optimering för en annan datastruktur, till exempel grafik. Uppsättning av denna flagga och läge skulle kunna minska filstorleken avsevärt men samtidigt avsevärt minska prestanda för konvertering. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | Strategi för att bearbeta symboler från Unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | Strategi för att kopiera kodningsdata för symboliska teckensnitt om symboliska TrueType font har mer än en kodningsundertabell. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | Åtgärd för bildmaskerade objekt |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | Regler för att lösa problem med unicode-mappning. Kan vara null. |

## Fält

| namn | Beskrivning |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | Strategi för att justera text. Denna parameter har betydelse endast när flagga[`AlignText`](./aligntext) är satt till sant. |

### Se även

* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
