---
title: "Klass PdfViewer"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfViewer klass. Representerar en klass för att visa eller skriva ut en pdf"
type: docs
weight: 4750
url: /sv/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

Representerar en klass för att visa eller skriva ut en pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Initierar ett nytt `PdfViewer`-objekt. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Initierar ett nytt `PdfViewer`-objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om filen ska skrivas ut med optimerad storlek.  Om falskt skrivs sidan ut utan skalning. Om sant skrivs sidan ut med skalning för att passa det utskrivbara området. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om filen ska skrivas ut med automatisk rotation |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Hämtar eller anger ett AutoRotateMode‑värde som indikerar rotationsriktning |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Hämtar eller anger formulärets presentationsläge. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Hämtar eller anger ett värde som indikerar horisontell justering |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Hämtar sidantalet för den aktuella Pdf-filen. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Hämtar eller anger lösenord för inmatningsdokumentet. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om sidan skrivs ut i gråskala. Standardvärdet är falskt. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Anger eller hämtar ett läge för PdfViewer att skriva ut som bild. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Hämtar eller anger namn på dokumentet i skrivarens kö när dokumentet skrivs ut. Standardvärdet är filnamnet. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om sidnumreringsdialogen ska visas vid utskrift. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Hämtar resultatet av utskriftsjobbet. Om det lyckas returneras null; annars ett undantagsobjekt. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Hämtar eller anger renderingsalternativ. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Hämtar eller anger upplösning vid visning och utskrift. Högre upplösning ger lägre hastighet. Standardvärdet är 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Hämtar eller anger ett flyttal som indikerar skalningsfaktor. Standardvärdet är 1,0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Hämtar/anger användningen av konvertering av pdf-sida till en mellanstegs-png-fil under utskrift i fil-läge. Använd detta när storleken på utdatafilen är viktig. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Hämtar eller anger ett värde som indikerar vertikal justering. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Initierar fasaden. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Initierar fasaden. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Initierar fasaden. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Stänger fasaden. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Hämta sidorna i den aktuella pdf-filen. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Avkodar en sida i en Pdf-fil. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Frigör facade-resurserna. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Hämtar standardinställningarna för sidan. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Hämtar standardinställningarna för skrivaren. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Skriver ut Pdf-dokumentet med standardskrivaren. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Skriver ut Pdf-dokumentet med skrivarinställningar. Utskrifts sidstorlek anpassas till dokumentets första sidstorlek. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Skriver ut Pdf-dokumentet med inställningar. Om dokumentets storlek inte motsvarar sidstorleken kommer den att utökas för att passa sidstorleken. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Skriver ut Pdf-dokumentet med en installationsdialog. Välj en skrivare via dialogen. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Öppnar och skriver ut en stor Pdf-ström. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Öppnar och skriver ut en stor Pdf-fil. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Öppnar och skriver ut en stor Pdf-ström med angivna skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Öppnar och skriver ut en stor Pdf-fil med angivna skrivarinställningar. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Öppnar och skriver ut en stor Pdf-ström med angivna sidinställningar och skrivarinställningar. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Öppnar och skriver ut en stor Pdf-fil med angivna sidinställningar och skrivarinställningar. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Sparar det resulterande PDF-dokumentet till en ström. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Sparar det resulterande PDF-dokumentet till en fil. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments)(params Document[]) | Skriver ut flera PDF-dokument med standardskrivare och sidinställningar. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_7)(params Stream[]) | Skriver ut flera PDF-dokument från de angivna strömmarna med standardskrivare och sidinställningar. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_8)(params string[]) | Skriver ut flera PDF-dokument med standardskrivare och sidinställningar. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_1)(PrinterSettings, params Document[]) | Skriver ut flera PDF-dokument med de angivna skrivarinställningarna. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_5)(PrinterSettings, params Stream[]) | Skriver ut flera PDF-dokument från de angivna strömmarna med de angivna skrivarinställningarna. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_6)(PrinterSettings, params string[]) | Skriver ut flera PDF-dokument med de angivna skrivarinställningarna. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_2)(PrinterSettings, PageSettings, params Document[]) | Skriver ut flera PDF-dokument med de angivna skrivar- och sidinställningarna. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_3)(PrinterSettings, PageSettings, params Stream[]) | Skriver ut flera PDF-dokument från de angivna strömmarna med de angivna skrivar- och sidinställningarna. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_4)(PrinterSettings, PageSettings, params string[]) | Skriver ut flera PDF-dokument med de angivna skrivar- och sidinställningarna. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Inträffar innan utskriften startar och möjliggör att tillhandahålla anpassade utskrifts‑hanterare istället för standard. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Inträffar när utskriften av en sida avslutas i PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Lägger till/avlägsnar prenumeration på händelsen för utskrift av sista sidan. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Lägger till/avlägsnar prenumeration på händelsen för utskrift av sista sidan. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Inträffar innan en sida börjar skrivas ut. |

### Se även

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


