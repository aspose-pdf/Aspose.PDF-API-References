---
title: "Klass PdfPageEditor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfPageEditor-klass. Representerar en klass för att redigera PDF-fils sida inklusive rotering, zoomning, flyttning av position och ändring av sidstorlek."
type: docs
weight: 4710
url: /sv/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Representerar en klass för att redigera PDF file:s sida, inklusive rotera sida, zooma sida, flytta position och ändra sidstorlek.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Konstruktor för PdfPageEditor-klass. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Konstruktor för PdfPageEditor-klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Hämtar eller anger visningstid för sidor. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Hämtar eller anger den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | En hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet för nyckeln representerar rotationen i grader. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Hämtar eller anger sidstorleken för utdatafilen. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Hämtar eller anger sidnumren som ska redigeras. Som standard redigeras varje sida. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Hämtar eller anger rotationen för sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Hämtar eller anger varaktigheten för övergångseffekten. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Hämtar eller anger övergångsstilen som ska användas när man går till den här sidan från en annan under en presentation. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Hämtar eller anger den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Hämtar eller anger zoomkoefficient. Värdet 1,0 motsvarar 100 %. Standardvärdet är 1,0. Följande exempel visar hur man ändrar zoom för dokumentets sidor. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Tillämpar ändringar som gjorts på dokumentets sidor. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rensar Aspose.Pdf.Document som är bunden till en fasad. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Returnerar storleken på den angivna rutan i dokumentet. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Returnerar rotationen för den angivna sidan. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Returnerar det totala antalet sidor. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Returnerar sidstorleken för den angivna sidan. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Flyttar origo från (0, 0) till den angivna punkten. Origo är vänster‑nedre och enheten är point (1 tum = 72 punkter). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Sparar ändrat dokument till en ström. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Sparar ändrat dokument till en fil. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Vertikala persienner |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Vertikala persienner |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Botten‑till‑topp svep |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Diagonal glitter |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Den gamla sidan löser upp sig |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Inåtriktad ruta |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Vänster-höger glitter |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Vänster-höger svep |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Utåtriktad ruta |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Höger-vänster svep |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | IN horisontell delning |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Ut horisontell delning |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | In vertikal delning |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Ut vertikal delning |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Topp-botten glitter |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Topp-botten svep |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


