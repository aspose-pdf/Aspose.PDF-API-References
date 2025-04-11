---
title: Class PdfContentEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfContentEditor-Klasse. Stellt eine Klasse zum Bearbeiten des Inhalts von PDF-Dateien dar
type: docs
weight: 4430
url: /de/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor-Klasse

Stellt eine Klasse zum Bearbeiten des Inhalts von PDF-Dateien dar.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | Der Konstruktor des PdfContentEditor-Objekts. |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | Initialisiert ein neues `PdfContentEditor`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | Eine Menge von Parametern für die Textersetzungsoperation |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | Gibt die Textbearbeitungsoptionen zurück oder setzt sie. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | Gibt die Textersetzungsoptionen zurück oder setzt sie. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | Gibt die Textsuchoptionen zurück oder setzt sie. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | Fügt eine zusätzliche Aktion für das Dokumentereignis hinzu. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | Fügt eine Dokumentenanhang ohne Annotation hinzu. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | Fügt eine Dokumentenanhang ohne Annotation hinzu. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | Bindet einen PDF-Stream zur Bearbeitung. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | Bindet eine PDF-Datei zur Bearbeitung. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | Ändert die Ansichtseinstellungen. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | Schließt das geöffnete Dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | Erstellt ein Lesezeichen mit der angegebenen Aktion. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | Erstellt eine Caret-Annotation. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | Erstellt einen Link zu benutzerdefinierten Aktionen im PDF-Dokument. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | Erstellt eine Dateianhang-Annotation. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | Erstellt eine Dateianhang-Annotation. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | Erstellt eine Dateianhang-Annotation. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Erstellt eine Dateianhang-Annotation. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | Erstellt eine Freitext-Annotation im PDF-Dokument |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | Erstellt einen Link zu JavaScript im PDF-Dokument. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Erstellt eine Linien-Annotation. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | Erstellt einen lokalen Link im PDF-Dokument. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | Erstellt einen lokalen Link im PDF-Dokument. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Erstellt einen lokalen Link im PDF-Dokument. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | Erstellt eine Markup-Annotation im PDF-Dokument. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | Erstellt Film-Annotationen. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | Erstellt einen Link zu einer anderen Seite im PDF-Dokument. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Erstellt einen Link zu einer anderen Seite im PDF-Dokument. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Erstellt einen Link zu einer anderen Seite im PDF-Dokument. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | Erstellt eine Polygon-Annotation. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | Erstellt eine Polyline-Annotation. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | Erstellt eine Popup-Annotation im PDF-Dokument. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | Erstellt eine Gummistempel-Annotation. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | Erstellt eine Gummistempel-Annotation. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | Erstellt eine Gummistempel-Annotation. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | Erstellt Sound-Annotationen. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | Erstellt eine Quadrat-Kreis-Annotation. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | Erstellt eine Text-Annotation im PDF-Dokument |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | Erstellt einen Weblink im PDF-Dokument. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | Erstellt einen Weblink im PDF-Dokument. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Erstellt einen Weblink im PDF-Dokument. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | Löscht alle Anhänge im PDF-Dokument. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | Löscht alle Bilder aus dem PDF-Dokument. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | Löscht die angegebenen Bilder auf der angegebenen Seite. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | Löscht mehrere Stempel auf der angegebenen Seite nach Stempelindizes. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | Löscht einen Stempel nach ID von allen Seiten des Dokuments. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | Löscht den Stempel auf der angegebenen Seite nach Stempel-ID. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | Löscht Stempel auf der angegebenen Seite nach mehreren Stempel-IDs. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | Erstellt eine Kurven-Annotation. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | Extrahiert die Sammlung von Link-Instanzen, die im PDF-Dokument enthalten sind. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | Gibt ein Array von Stempeln auf der Seite zurück. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | Gibt die Ansichtseinstellungen zurück. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | Blendet den Stempel aus. Nach dem Ausblenden kann die Sichtbarkeit des Stempels mit der Methode ShowStampById wiederhergestellt werden. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | Ändert die Position des Stempels auf der Seite. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | Ändert die Position des Stempels auf der Seite. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | Entfernt die Öffnungsaktion aus dem Dokument. Diese Operation ist nützlich, wenn mehrere Dokumente, die eine explizite 'GoTo'-Aktion beim Start verwenden, zusammengeführt werden. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | Ersetzt das angegebene Bild auf der angegebenen Seite des PDF-Dokuments durch ein anderes Bild. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | Ersetzt Text in der PDF-Datei. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | Ersetzt Text in der PDF-Datei und setzt die Schriftgröße. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | Ersetzt Text in der PDF-Datei unter Verwendung des angegebenen [`TextState`](../../aspose.pdf.text/textstate/) Objekts. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. Das [`TextState`](../../aspose.pdf.text/textstate/) Objekt (Schriftfamilie, Farbe) kann für den ersetzten Text angegeben werden. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | Zeigt den Stempel an, der von HiddenStampById ausgeblendet wurde. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | Ein Dokumentereignistyp. Schließt ein Dokument. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | Ein Dokumentereignistyp. Öffnet ein Dokument. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | Ein Dokumentereignistyp. Führt eine Aktion nach dem Drucken aus. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | Ein Dokumentereignistyp. Führt eine Aktion nach dem Speichern aus. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | Ein Dokumentereignistyp. Führt eine Aktion vor dem Drucken aus. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | Ein Dokumentereignistyp. Führt eine Aktion vor dem Speichern aus. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)