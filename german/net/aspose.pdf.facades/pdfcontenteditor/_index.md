---
title: PdfContentEditor
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse zum Bearbeiten des Inhalts einer PDF-Datei.
type: docs
weight: 2440
url: /de/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

Repräsentiert eine Klasse zum Bearbeiten des Inhalts einer PDF-Datei.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor#constructor)() | Der Konstruktor des PdfContentEditor-Objekts. |
| [PdfContentEditor](pdfcontenteditor#constructor_1)(Document) | Initialisiert neu[`PdfContentEditor`](../pdfcontenteditor) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy) { get; set; } | Ein Satz von Parametern für den Textersetzungsvorgang |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions) { get; set; } | Ruft Textbearbeitungsoptionen ab oder setzt sie. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions) { get; set; } | Holt oder setzt Optionen zum Ersetzen von Text. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions) { get; set; } | Ruft Textsuchoptionen ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction)(string, string) | Fügt zusätzliche Aktion für Dokumentereignis hinzu. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment_1)(string, string) | Fügt einen Dokumentanhang ohne Anmerkung hinzu. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment)(Stream, string, string) | Fügt einen Dokumentanhang ohne Anmerkung hinzu. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_1)(Stream) | Bindet einen PDF-Stream zur Bearbeitung. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_2)(string) | Bindet eine PDF-Datei zur Bearbeitung. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference)(int) | Ändert die Anzeigeeinstellungen. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close)() | Schließt geöffnetes Dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink)(Rectangle, string, int) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_1)(Rectangle, string, int, Color) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction)(string, Color, bool, bool, string, string, string) | Erstellt ein Lesezeichen mit der angegebenen Aktion. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret)(int, Rectangle, Rectangle, string, string, Color) | Erstellt Caret-Annotation. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink)(Rectangle, int, Color, Enum[]) | Erstellt einen Link zu benutzerdefinierten Aktionen im PDF-Dokument. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_2)(Rectangle, string, string, int, string) | Erstellt Anmerkungen zu Dateianhängen. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment)(Rectangle, string, Stream, string, int, string) | Erstellt Anmerkungen zu Dateianhängen. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_3)(Rectangle, string, string, int, string, double) | Erstellt Anmerkungen zu Dateianhängen. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Erstellt Anmerkungen zu Dateianhängen. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext)(Rectangle, string, int) | Erstellt Freitextanmerkungen im PDF-Dokument |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink)(string, Rectangle, int, Color) | Erstellt einen Link zu JavaScript im PDF-Dokument. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Erstellt Linienbeschriftung. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink)(Rectangle, int, int) | Erstellt einen lokalen Link im PDF-Dokument. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_1)(Rectangle, int, int, Color) | Erstellt einen lokalen Link im PDF-Dokument. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Erstellt einen lokalen Link im PDF-Dokument. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup)(Rectangle, string, int, int, Color) | Erstellt Markup-Anmerkungen im PDF-Dokument. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie)(Rectangle, string, int) | Erstellt Filmanmerkungen. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink)(Rectangle, string, int, int) | Erstellt einen Link zu einer anderen PDF-Dokumentseite. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Erstellt einen Link zu einer anderen PDF-Dokumentseite. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Erstellt einen Link zu einer anderen PDF-Dokumentseite. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon)(LineInfo, int, Rectangle, string) | Erstellt eine Polygonanmerkung. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline)(LineInfo, int, Rectangle, string) | Erstellt Polylinienbeschriftung. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup)(Rectangle, string, bool, int) | Erstellt eine Popup-Anmerkung im PDF-Dokument. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp)(int, Rectangle, string, Color, Stream) | Erstellt eine Stempelanmerkung. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_1)(int, Rectangle, string, Color, string) | Erstellt eine Stempelanmerkung. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_2)(int, Rectangle, string, string, Color) | Erstellt eine Stempelanmerkung. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound)(Rectangle, string, string, int, string) | Erstellt Tonanmerkungen. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle)(Rectangle, string, Color, bool, int, int) | Erstellt eine Quadrat-Kreis-Anmerkung. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext)(Rectangle, string, string, bool, string, int) | Erstellt Textanmerkungen im PDF-Dokument |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink)(Rectangle, string, int) | Erstellt einen Weblink im PDF-Dokument. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_1)(Rectangle, string, int, Color) | Erstellt einen Weblink im PDF-Dokument. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Erstellt einen Weblink im PDF-Dokument. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments)() | Löscht alle Anhänge im PDF-Dokument. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage)() | Löscht alle Bilder aus dem PDF-Dokument. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage_1)(int, int[]) | Löscht die angegebenen Bilder auf der angegebenen Seite. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp)(int, int[]) | Löscht mehrere Stempel auf der angegebenen Seite nach Stempelindizes. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid)(int) | Stempel nach ID von allen Seiten des Dokuments löschen. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid_1)(int, int) | Löscht Stempel auf der angegebenen Seite nach Stempel-ID. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids_1)(int[]) | Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids)(int, int[]) | Löscht Stempel auf der angegebenen Seite nach mehreren Stempel-IDs. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve)(LineInfo, int, Rectangle, string) | Erstellt eine Kurvenbeschriftung. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink)() | Extrahiert die Sammlung von Link-Instanzen, die im PDF-Dokument enthalten sind. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps)(int) | Gibt ein Array von Stempeln auf der Seite zurück. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference)() | Gibt die Ansichtseinstellung zurück. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid)(int, int) | Blendet den Stempel aus. Nach dem Ausblenden kann die Sichtbarkeit des Stempels mit der ShowStampById-Methode wiederhergestellt werden. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp)(int, int, double, double) | Ändert die Position des Stempels auf der Seite. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid)(int, int, double, double) | Ändert die Position des Stempels auf der Seite. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction)() | Entfernt die offene Aktion aus dem Dokument. Diese Operation ist nützlich, wenn mehrere Dokumente verkettet werden, die beim Start eine explizite „GoTo“-Aktion verwenden. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage)(int, int, string) | Ersetzt das angegebene Bild auf der angegebenen Seite des PDF-Dokuments durch ein anderes Bild. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_2)(string, string) | Ersetzt Text in der PDF-Datei. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext)(string, int, string) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_4)(string, string, int) | Ersetzt Text in der PDF-Datei und legt die Schriftgröße fest. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_3)(string, string, TextState) | Ersetzt Text in der PDF-Datei mit angegebenem[`TextState`](../../aspose.pdf.text/textstate) Objekt. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_1)(string, int, string, TextState) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite.[`TextState`](../../aspose.pdf.text/textstate) Objekt (Schriftfamilie, Farbe) kann angegeben werden, um Text zu ersetzen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid)(int, int) | Zeigt einen Stempel, der durch HiddenStampById ausgeblendet wurde. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose) | Ein Dokumentereignistyp. Schließt ein Dokument. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen) | Ein Dokumentereignistyp. Öffnet ein Dokument. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted) | Ein Dokumentereignistyp. Nach dem Drucken eine Aktion ausführen. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved) | Ein Dokumentereignistyp. Nach dem Speichern eine Aktion ausführen. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint) | Ein Dokumentereignistyp. Vor dem Drucken eine Aktion ausführen. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave) | Ein Dokumentereignistyp. Vor dem Speichern eine Aktion ausführen. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
