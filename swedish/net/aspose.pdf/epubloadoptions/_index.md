---
title: EpubLoadOptions
second_title: Aspose.PDF för .NET API Referens
description: Innehåller alternativ för att ladda/importera EPUB-fil till pdf-dokument.
type: docs
weight: 2090
url: /sv/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Innehåller alternativ för att ladda/importera EPUB-fil till pdf-dokument.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EpubLoadOptions](epubloadoptions#constructor)() | Skapar standardinläsningsalternativ för att konvertera EPUB-fil till pdf-dokument. Standard pdf-sidastorlek - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions#constructor_1)(SizeF) | Skapar laddningsalternativ med angiven sidstorlek. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Representerar filformat som[`LoadOptions`](../loadoptions) beskriver. |
| [Margin](../../aspose.pdf/epubloadoptions/margin) { get; set; } | Får referens på objekt som representerar marginalinformation. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize) { get; } | Hämtar eller ställer in utgående sidstorlek för import. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction enum-objektet som anger antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och Load-operationen fortsätter, men användaren kan också returnera Avbryt i vilket fall Load-operationen bör upphöra. |

## Fält

| namn | Beskrivning |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode) | Representerar användningssätt för marginalområdet - definierar behandling av instruktioner (om några) av CSS för importerat document relaterat till användning av marginaler. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode) | OBS! Funktionen implementerad men ännu inte lagt till offentligt API eftersom blockeringsproblem i OSHARED-lagret avslöjats för exempeldokument. Representerar användningssätt för sidstorlek under konvertering. Format (som HTML, EPUB etc), har vanligtvis flytande design , så det tillåter att passa required pagesize. Men ibland har innehåll specificerat horisontella positioner eller storlek som inte tillåter att innehållet läggs in i önskad sidstorlek. I sådana fall kan vi definiera vad som ska göras i det här fallet (dvs. när storleken på innehållet inte passar krävs initial sidstorlek av resultat PDF-dokument). |

### Se även

* class [LoadOptions](../loadoptions)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->