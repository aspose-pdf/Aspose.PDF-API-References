---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer klass. Representerar en klass för att visa eller skriva ut en pdf
type: docs
weight: 4630
url: /sv/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer klass

Representerar en klass för att visa eller skriva ut en pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Initierar ett nytt `PdfViewer` objekt. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Initierar ett nytt `PdfViewer` objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om filen ska skrivas ut med optimerad storlek. Om false skriv ut sidan utan sidskalning. Om true skriv ut sidan med skalning för att passa det utskrivbara området. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om filen ska skrivas ut med automatisk rotation |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Hämtar eller sätter ett AutoRotateMode-värde som indikerar rotationsriktning |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Hämtar eller sätter sidkoordinattype (Media/Crop boxes). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Hämtar eller sätter formulärpresentationläge. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Hämtar eller sätter ett värde som indikerar horisontell justering |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Hämtar sidantalet för den aktuella Pdf-filen. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Hämtar eller sätter inmatningsdokumentets lösenord. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om sidan skrivs ut i gråskala. Som standard är det false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Sätter eller hämtar ett läge för PdfViewer att skriva ut som bild. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Hämtar eller sätter namnet på dokumentet i skrivarkön när dokumentet skrivs ut. Standardvärdet är filnamnet. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om sidnumret dialogen ska visas vid utskrift. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Hämtar resultatet av utskriftsjobbet. Om det lyckas är det null; annars, undantagsobjekt. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Hämtar eller sätter renderingsalternativ. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Hämtar eller sätter upplösning under visning och utskrift. Ju högre upplösning, desto långsammare hastighet. Standardvärdet är 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Hämtar eller sätter ett flyttal som indikerar skalfaktor. Standardvärdet är 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Hämtar/sätter användningen av konvertering av pdf-sidan till mellanliggande png-fil under utskrift i fil-läge. Använd det när storleken på utdatafilen är viktig. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Hämtar eller sätter ett värde som indikerar vertikal justering |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Initierar fasaden. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Initierar fasaden. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Initierar fasaden. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Stänger fasaden. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Hämtar sidorna från den aktuella pdf-filen. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Avkodar en sida från en Pdf-fil. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Avsätter fasadens resurser. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Hämtar standard sidinställningar. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Hämtar standard skrivarinställningar. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Skriver ut Pdf-dokumentet med standard skrivare. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Skriver ut Pdf-dokumentet med skrivarinställningar. Utskriftsstorleken kommer att passa dokumentets första sidstorlek. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Skriver ut Pdf-dokumentet med inställningar. Om dokumentstorleken inte motsvarar sidstorleken, kommer den att utvidgas för att passa sidstorleken. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Skriver ut Pdf-dokumentet med en installationsdialog. Välj en skrivare med dialogrutan. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Öppnar och skriver ut en stor Pdf-ström. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Öppnar och skriver ut en stor Pdf-fil. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Öppnar och skriver ut en stor Pdf-ström med angivna skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Öppnar och skriver ut en stor Pdf-fil med angivna skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Öppnar och skriver ut en stor Pdf-ström med angivna sidinställningar och skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Öppnar och skriver ut en stor Pdf-fil med angivna sidinställningar och skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Sparar det resulterande PDF-dokumentet till ström. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Sparar det resulterande PDF-dokumentet till fil. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Inträffar innan utskriften börjar och tillåter att tillhandahålla anpassade utskriftsbehandlare istället för den förvalda. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Inträffar när utskriften av en sida avslutas i PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Lägger till/avlägsnar prenumeration på händelsen för utskrift av sista sidan. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Lägger till/avlägsnar prenumeration på händelsen för utskrift av sista sidan. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Inträffar innan en sida börjar skrivas ut. |

### Se Även

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)