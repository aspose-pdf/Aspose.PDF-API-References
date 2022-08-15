---
title: PdfViewer
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för att visa eller skriva ut en pdf.
type: docs
weight: 2640
url: /sv/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

Representerar en klass för att visa eller skriva ut en pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfViewer](pdfviewer#constructor)() | Initierar ny[`PdfViewer`](../pdfviewer) objekt. |
| [PdfViewer](pdfviewer#constructor_1)(Document) | Initierar ny[`PdfViewer`](../pdfviewer) objekt. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize) { get; set; } | Hämtar eller ställer in ett boolvärde som anger om filen ska skrivas ut med optimerad storlek.  Om falskt skriv ut sida utan sidskalning. Om sant skriv ut sida med skalning för att passa till det utskrivbara området. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate) { get; set; } | Hämtar eller ställer in ett boolvärde som anger om filen ska skrivas ut med auto rotation |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode) { get; set; } | Hämtar eller ställer in ett AutoRotateMode-värde som anger rotationsriktning |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype) { get; set; } | Hämtar eller ställer in sidkoordinattypen (Media/Crop-rutor). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode) { get; set; } | Hämtar eller ställer in formulärpresentationsläge. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment) { get; set; } | Hämtar eller ställer in ett värde som indikerar horisontell alignment |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount) { get; } | Hämtar sidantal för den aktuella PDF-filen. |
| [Password](../../aspose.pdf.facades/pdfviewer/password) { get; set; } | Hämtar eller ställer in lösenord för inmatningsdokument. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om sidan skrivs ut i gråskala. Som standard är false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage) { get; set; } | Ställer in eller hämtar ett läge för PdfViewer att skriva ut som bild. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname) { get; set; } | Hämtar eller ställer in namnet på dokumentet i skrivarkön när dokumentet skrivs ut. Standardvärdet är filnamn. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om sidnummerdialogrutan skapas vid utskrift. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus) { get; } | Får resultatet av utskriftsjobbet. Om framgång än null; annars undantagsobjekt. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions) { get; set; } | Hämtar eller ställer in renderingsalternativ. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution) { get; set; } | Får eller ställer in upplösning under visning och utskrift. Ju högre upplösning, desto lägre hastighet. Standardvärdet är 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor) { get; set; } | Hämtar eller sätter ett flyttalsvärde som indikerar skalfaktor. Standardvärdet är 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage) { get; set; } | Får/ställer in användning av konvertering av pdf-sida till intermidiate png-fil under utskrift i filläge. Använd den när storleken på utdatafilen är viktig. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment) { get; set; } | Hämtar eller ställer in ett värde som indikerar vertikal alignment |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf)(Document) | Initierar fasaden. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_1)(Stream) | Initierar fasaden. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_2)(string) | Initierar fasaden. |
| [Close](../../aspose.pdf.facades/pdfviewer/close)() | Stänger fasaden. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages)() | Hämta sidor med aktuell pdf-fil. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage)(int) | Avkodar en sida i en pdf-fil. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose)() | Förfogar över fasadresurserna. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings)() | Hämtar standardsidans inställningar. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings)() | Hämtar standardskrivarinställningarna. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument)() | Skriver ut PDF-dokumentet med standardskrivare. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings_1)(PrinterSettings) | Skriver ut PDF-dokumentet med skrivarinställningar. Utgående sidstorlek kommer att passa dokumentets första sidstorlek. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings)(PageSettings, PrinterSettings) | Skriver ut PDF-dokumentet med inställningar. Om dokumentstorleken inte är kompatibel med sidstorleken kommer pdf.kit att utöka den för att passa sidstorleken. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup)() | Skriver ut PDF-dokumentet med en inställningsdialogruta. Välj en skrivare med hjälp av dialogrutan. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf)(Stream) | Öppnar och skriver ut en stor PDF-ström. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_3)(string) | Öppnar och skriver ut en stor pdf-fil. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_2)(Stream, PrinterSettings) | Öppnar och skriver ut en stor PDF-ström med specificerade skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_5)(string, PrinterSettings) | Öppnar och skriver ut en stor pdf-fil med specificerade skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Öppnar och skriver ut en stor PDF-ström med angivna sidinställningar och skrivarinställningar. Om din Pdf -fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_4)(string, PageSettings, PrinterSettings) | Öppnar och skriver ut en stor pdf-fil med angivna sidinställningar och skrivarinställningar. Om din Pdf -fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save)(Stream) | Sparar resultatet PDF-dokument för att streama. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save_1)(string) | Sparar resultatet PDF-dokument till fil. |

### Se även

* interface [IFacade](../ifacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
