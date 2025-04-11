---
title: Class PdfAOptionsBase
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAOptionsBase klass. Representerar basklassen för PdfAConverter-pluginalternativ. Denna klass tillhandahåller egenskaper och metoder för att konfigurera PDF/A-konverterings- och valideringsprocessen
type: docs
weight: 9010
url: /sv/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## PdfAOptionsBase klass

Representerar basklassen för [`PdfAConverter`](../pdfaconverter/) pluginalternativ. Denna klass tillhandahåller egenskaper och metoder för att konfigurera PDF/A-konverterings- och valideringsprocessen.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om ytterligare medel är nödvändiga för att bevara textjusteringen under PDF/A-konverteringsprocessen. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Hämtar eller ställer in åtgärden som ska vidtas för objekt som inte kan konverteras. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Hämtar eller ställer in strategin för att ta bort typsnitt för att minimera utdatafilens storlek under PDF/A-konverteringsprocessen. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Hämtar alternativen för att bearbeta typsnitt som inte kan bäddas in i dokumentet. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Hämtar eller ställer in filnamnet för ICC (International Color Consortium) profil som ska användas för PDF/A-konverteringen istället för den förvalda. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Hämtar samling av datakällor |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om lågminnesläge är aktiverat under PDF/A-konverteringsprocessen. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Hämtar eller ställer in datakällan för loggutdata. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Hämtar flaggorna som styr PDF/A-konverteringen för fall när den käll-PDF-dokumentet inte överensstämmer med PDF-specifikationen. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om man ska försöka minska filstorleken under PDF/A-konverteringsprocessen. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Hämtar eller ställer in versionen av PDF/A-standarden som ska användas för validering eller konvertering. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Hämtar eller ställer in strategin för att bearbeta symboler i Private Use Area (PUA) i PDF-dokumentet. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Hämtar eller ställer in åtgärden som ska vidtas under konverteringen av bilder med mjuka masker. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Hämtar eller ställer in strategin för att koda symboliska typsnitt när man konverterar till PDF/A-format. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Hämtar eller ställer in reglerna för att bearbeta ToUnicode CMap-tabeller och inte kopplade till Unicode-symboler under PDF/A-konverteringsprocessen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Lägger till ny datakälla till samlingen |

### Se Även

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)