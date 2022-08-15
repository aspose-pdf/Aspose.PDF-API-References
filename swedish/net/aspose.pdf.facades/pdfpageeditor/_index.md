---
title: PdfPageEditor
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för att redigera PDF-filens sida inklusive roterande sida zoomande sida flytta position och ändra sidstorlek.
type: docs
weight: 2600
url: /sv/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Representerar en klass för att redigera PDF-filens sida, inklusive roterande sida, zoomande sida, flytta position och ändra sidstorlek.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfPageEditor](pdfpageeditor#constructor)() | Konstruktör för klassen PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor#constructor_1)(Document) | Konstruktör för klassen PdfPageEditor. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration) { get; set; } | Hämtar eller ställer in visningslängd för sidor. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment) { get; set; } | Hämtar eller ställer in den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations) { get; set; } | En hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet på nyckeln representerar rotationen i grader. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize) { get; set; } | Hämtar eller ställer in utdatafilens sidstorlek. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages) { get; set; } | Hämtar eller ställer in sidnumren som ska redigeras. Som standard skulle varje sida redigeras. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation) { get; set; } | Hämtar eller ställer in rotationen av sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration) { get; set; } | Hämtar eller ställer in varaktigheten för övergångseffekten. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype) { get; set; } | Hämtar eller ställer in övergångsstil som ska användas när du flyttar till den här sidan från en annan under en presentation. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype) { get; set; } | Hämtar eller ställer in den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom) { get; set; } | Hämta eller ställer in zoomkoefficient. Värde 1.0 motsvarar 100%. Standardvärdet är 1.0.  Följande exempel visar hur man ändrar zoom på dokumentsidorna. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges)() | Tillämpa ändringar som gjorts på dokumentsidorna. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Kastar Aspose.Pdf.Dokument bunden med en fasad. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize)(int, string) | Returnerar storleken på angiven ruta i dokumentet. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation)(int) | Returnerar rotationen av angiven sida. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages)() | Returnerar totalt antal sidor. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize)(int) | Returnerar sidstorleken för den angivna sidan. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition)(float, float) | Flyttar ursprunget från (0, 0) till den punkt som utsetts. Ursprunget är vänster-ned och enheten är punkt (1 tum = 72 poäng). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save)(Stream) | Sparar ändrat dokument i ström. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save_1)(string) | Sparar ändrat dokument i fil. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh) | Vertikala persienner |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv) | Vertikala persienner |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe) | Botten-Top Torka |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter) | Diagonalt glitter |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve) | Den gamla sidan löses upp |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox) | Invändig låda |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter) | Vänster-Höger Glitter |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe) | Vänster-Höger Torka |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox) | Outward Box |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe) | Höger-vänster torka |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin) | IN Horisontell Split |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout) | Ut Horisontell Split |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin) | I Vertikal Split |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout) | Ut Vertikal Split |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter) | Topp-botten glitter |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe) | Torka uppifrån och ned |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
