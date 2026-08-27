---
title: "Klass PdfAValidateOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.PdfAValidateOptions-klass. Representerar alternativ för validering av PDF/A-efterlevnad för PDF-dokument med PdfAConverter-plugin."
type: docs
weight: 9180
url: /sv/net/aspose.pdf.plugins/pdfavalidateoptions/
---
## PdfAValidateOptions class

Representerar alternativ för validering av PDF/A-efterlevnad för PDF-dokument med [`PdfAConverter`](../pdfaconverter/) plugin.

```csharp
public sealed class PdfAValidateOptions : PdfAOptionsBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfAValidateOptions](pdfavalidateoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Hämtar eller anger ett värde som indikerar om ytterligare medel behövs för att bevara textjustering under PDF/A-konverteringsprocessen. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Hämtar eller anger åtgärden som ska vidtas för objekt som inte kan konverteras. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Hämtar eller anger strategin för att ta bort teckensnitt för att minimera utdatafilens storlek under PDF/A‑konverteringsprocessen. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Hämtar alternativ för att bearbeta teckensnitt som inte kan bäddas in i dokumentet. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Hämtar eller anger filnamnet på ICC‑profilen (International Color Consortium) som ska användas för PDF/A‑konverteringen i stället för standardprofilen. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Hämtar samling av datakällor |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Hämtar eller anger ett värde som indikerar om lågt minnesläge är aktiverat under PDF/A‑konverteringsprocessen. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Hämtar eller anger datakällan för loggutdata. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Hämtar flaggorna som styr PDF/A‑konverteringen för fall då källdokumentet PDF inte överensstämmer med PDF‑specifikationen. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Hämtar eller anger ett värde som indikerar om filstorleken ska försökas minska under PDF/A‑konverteringsprocessen. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Hämtar eller anger versionen av PDF/A‑standarden som ska användas för validering eller konvertering. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Hämtar eller anger strategin för att bearbeta Private Use Area (PUA)‑symboler i PDF‑dokumentet. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Hämtar eller anger åtgärden som ska vidtas under konvertering av bilder med mjuka masker. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Hämtar eller anger strategin för kodning av symbolteckensnitt vid konvertering till PDF/A‑format. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Hämtar eller anger reglerna för att bearbeta ToUnicode CMap‑tabeller som inte är länkade till Unicode‑symboler under PDF/A‑konverteringsprocessen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Lägger till ny datakälla i samlingen |

### Se även

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


