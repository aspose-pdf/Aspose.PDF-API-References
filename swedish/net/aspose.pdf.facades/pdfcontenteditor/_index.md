---
title: "Klass PdfContentEditor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfContentEditor‑klass. Representerar en klass för att redigera innehållet i PDF‑filer"
type: docs
weight: 4550
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

Representerar en klass för att redigera PDF file:s innehåll.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | Konstruktorn för PdfContentEditor‑objektet. |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | Initierar ett nytt `PdfContentEditor`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | En uppsättning parametrar för ersättningsoperation av text |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | Hämtar eller anger alternativ för textredigering. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | Hämtar eller anger alternativ för textersättning. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | Hämtar eller anger alternativ för textsökning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | Lägger till ytterligare åtgärd för dokumenthändelse. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | Lägger till dokumentbilaga utan annotation. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | Lägger till dokumentbilaga utan annotation. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | Kopplar en PDF-ström för redigering. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | Kopplar en PDF-fil för redigering. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | Ändrar visningsinställningen. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | Stänger öppet dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | Skapar en länk för att starta ett program i PDF-dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | Skapar en länk för att starta ett program i PDF-dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Skapar en länk för att starta ett program i PDF-dokument. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | Skapar ett bokmärke med den angivna åtgärden. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | Skapar markörannotation. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | Skapar en länk till anpassade åtgärder i PDF-dokument. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | Skapar filbilageannotation. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | Skapar filbilageannotation. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | Skapar filbilageannotation. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Skapar filbilageannotation. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | Skapar fri text-annotation i PDF-dokument |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | Skapar en länk till JavaScript i PDF-dokument. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Skapar linjeannotation. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | Skapar en lokal länk i PDF-dokument. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | Skapar en lokal länk i PDF-dokument. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Skapar en lokal länk i PDF-dokument. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | Skapar markup-annotation i PDF-dokument. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | Skapar filmannotationer. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | Skapar en länk till en annan PDF-dokumentsida. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Skapar en länk till en annan PDF-dokumentsida. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Skapar en länk till en annan PDF-dokumentsida. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | Skapar polygonannotation. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | Skapar polylinjeannotation. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | Skapar popup-annotation i PDF-dokument. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | Skapar en gummistämpel-annotation. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | Skapar en gummistämpel-annotation. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | Skapar en gummistämpel-annotation. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | Skapar ljudannotationer. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | Skapar fyrkant-cirkel-annotation. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | Skapar textannotation i PDF-dokument |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | Skapar en webblänk i PDF-dokument. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | Skapar en webblänk i PDF-dokument. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Skapar en webblänk i PDF-dokument. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | Tar bort alla bilagor i PDF-dokument. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | Tar bort alla bilder från PDF-dokument. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | Tar bort de angivna bilderna på den angivna sidan. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | Tar bort flera stämplar på den angivna sidan efter stämpelindex. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | Ta bort stämpel efter ID från alla sidor i dokumentet. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | Tar bort stämpel på den angivna sidan efter stämpel-ID. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | Tar bort stämplar på den angivna sidan efter flera stämpel-ID:n. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | Skapar kurvannotation. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | Extraherar samlingen av Link-instanser som finns i PDF-dokument. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | Returnerar en array av stämplar på sidan. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | Returnerar visningspreferensen. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | Döljer stämpeln. Efter döljning kan stämpelns synlighet återställas med metoden ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | Ändrar positionen för stämpeln på sidan. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | Ändrar positionen för stämpeln på sidan. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | Tar bort öppningsåtgärden från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder en explicit 'GoTo'-åtgärd vid start. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | Ersätter den angivna bilden på den angivna sidan i PDF-dokumentet med en annan bild. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | Ersätter text i PDF-filen. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | Ersätter text i PDF-filen på den angivna sidan. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | Ersätter text i PDF-filen och anger teckenstorlek. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | Ersätter text i PDF-filen med det angivna [`TextState`](../../aspose.pdf.text/textstate/) objektet. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | Ersätter text i PDF-filen på den angivna sidan. [`TextState`](../../aspose.pdf.text/textstate/) objekt (teckensnittsfamilj, färg) kan anges för den ersatta texten. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | Visar stämpel som var dold av HiddenStampById. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | En dokumenthändelsetyp. Stänger ett dokument. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | En dokumenthändelsetyp. Öppnar ett dokument. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | En dokumenthändelsetyp. Utför en åtgärd efter utskrift. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | En dokumenthändelsetyp. Utför en åtgärd efter sparande. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | En dokumenthändelsetyp. Utför en åtgärd före utskrift. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | En dokumenthändelsetyp. Utför en åtgärd före sparande. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


