---
title: Class PdfAConvertOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConvertOptions klass. Representerar alternativ för att konvertera PDF-dokument till PDF/A-format med PdfAConverter-plugin
type: docs
weight: 8990
url: /sv/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions klass

Representerar alternativ för att konvertera PDF-dokument till PDF/A-format med [`PdfAConverter`](../pdfaconverter/) plugin.

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om ytterligare medel är nödvändiga för att bevara textjusteringen under PDF/A-konverteringsprocessen. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Hämtar eller ställer in åtgärden som ska vidtas för objekt som inte kan konverteras. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Hämtar eller ställer in strategin för att ta bort typsnitt för att minimera utdatafilens storlek under PDF/A-konverteringsprocessen. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Hämtar alternativen för att bearbeta typsnitt som inte kan bäddas in i dokumentet. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Hämtar eller ställer in filnamnet på ICC (International Color Consortium) profil som ska användas för PDF/A-konverteringen istället för den förvalda. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Hämtar samlingen av datakällor |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om lågminnesläge är aktiverat under PDF/A-konverteringsprocessen. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Hämtar eller ställer in datakällan för loggutdata. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Hämtar flaggorna som styr PDF/A-konverteringen för fall när käll-PDF-dokumentet inte motsvarar PDF-specifikationen. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om man ska försöka minska filstorleken under PDF/A-konverteringsprocessen. |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | Hämtar samlingen av tillagda mål (fil eller ström datakällor) för att spara operationens resultat. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Hämtar eller ställer in versionen av PDF/A-standarden som ska användas för validering eller konvertering. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Hämtar eller ställer in strategin för att bearbeta symboler i Private Use Area (PUA) i PDF-dokumentet. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Hämtar eller ställer in åtgärden som ska vidtas under konverteringen av bilder med mjuka masker. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Hämtar eller ställer in strategin för att koda symboliska typsnitt vid konvertering till PDF/A-format. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Hämtar eller ställer in reglerna för bearbetning av ToUnicode CMap-tabeller och som inte är kopplade till Unicode-symboler under PDF/A-konverteringsprocessen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Lägger till ny datakälla till samlingen |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | Lägger till ny resultatlagringsmål. |

### Se Även

* klass [PdfAOptionsBase](../pdfaoptionsbase/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)