---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfPageEditor klass. Representerar en klass för att redigera PDF-filer sida inklusive rotering av sida, zoomning av sida, flyttning av position och ändring av sidstorlek
type: docs
weight: 4590
url: /sv/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor klass

Representerar en klass för att redigera PDF-filens sida, inklusive rotering av sida, zoomning av sida, flyttning av position och ändring av sidstorlek.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Konstruktör för PdfPageEditor klass. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Konstruktör för PdfPageEditor klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Hämtar eller ställer in visningstid för sidor. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentfacaden som arbetas med. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Hämtar eller ställer in den horisontella justeringen av det ursprungliga PDF-innehållet på resultat sidan, standard är AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | En hashtabell som innehåller sidnummer och rotationsgrad, nyckeln representerar sidnumret, värdet av nyckeln representerar rotationen i grader. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Hämtar eller ställer in sidstorleken för utdatafilen. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Hämtar eller ställer in sidnumren som ska redigeras. Som standard skulle varje sida redigeras. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Hämtar eller ställer in rotationen av sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärde är 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Hämtar eller ställer in varaktigheten för övergångseffekten. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Hämtar eller ställer in övergångsstil som ska användas när man går till denna sida från en annan under en presentation. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Hämtar eller ställer in den vertikala justeringen av det ursprungliga PDF-innehållet på resultat sidan, standard är VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Hämtar eller ställer in zoomkoefficient. Värde 1.0 motsvarar 100%. Standardvärde är 1.0. Följande exempel visar hur man ändrar zoom på dokumentets sidor. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Tillämpa ändringar som gjorts på dokumentets sidor. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar facaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Avyttrar Aspose.Pdf.Document kopplad till en fasad. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avyttrar facaden. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Returnerar storleken på den angivna rutan i dokumentet. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Returnerar rotationen av den angivna sidan. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Returnerar det totala antalet sidor. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Returnerar sidstorleken för den angivna sidan. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Flyttar ursprunget från (0, 0) till den angivna punkten. Ursprunget är vänster-nederst och enheten är punkt (1 tum = 72 punkter). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Sparar det ändrade dokumentet i strömmen. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Sparar det ändrade dokumentet i filen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Vertikala Persienner |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Vertikala Persienner |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Botten-Topp Torkning |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Diagonal Glittra |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Den gamla sidan upplöses |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Inåtriktad Ruta |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Vänster-Höger Glittra |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Vänster-Höger Torkning |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Utåtriktad Ruta |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Höger-Vänster Torkning |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | IN Horisontell Delning |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Ut Horisontell Delning |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | In Vertikal Delning |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Ut Vertikal Delning |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Topp-Botten Glittra |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Topp-Botten Torkning |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../)