---
title: PdfExtractor
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse zum Extrahieren von Bildern und Text aus einem PDF-Dokument.
type: docs
weight: 2460
url: /de/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Klasse zum Extrahieren von Bildern und Text aus einem PDF-Dokument.

```csharp
public sealed class PdfExtractor : Facade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | Initialisiert neu[`PdfExtractor`](../pdfextractor) Objekt. |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | Initialisiert neu[`PdfExtractor`](../pdfextractor) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | Ruft die Endseite im Seitenbereich ab oder legt sie fest, in der der Extraktionsvorgang ausgeführt wird. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | Legt den Modus zum Extrahieren von Bildern fest. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | Legt den Modus für das Ergebnis des Extrahierens von Text fest. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | Ist wahr, wenn der Text hebräische oder arabische Symbole enthält. Dieser Fall muss besonders berücksichtigt werden, da Zeichenfolgenfunktionen ihr Verhalten ändern und Text von rechts nach links beginnen (außer Zahlen und andere Nicht-Textzeichen). |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | Ruft das Passwort der Eingabedatei ab oder legt es fest. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | Auflösung für extrahierte Bilder festlegen oder abrufen. Der Standardwert ist 150. Bilder mit einem höheren Auflösungswert sind klarer. Eine Erhöhung des Auflösungswerts führt jedoch zu einem erhöhten Zeit- und Speicherbedarf zum Extrahieren von Bildern. Normalerweise reicht es aus, um ein klares Bild zu erhalten um die Auflösung auf 150 oder 300 einzustellen. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | Ruft die Startseite im Seitenbereich ab oder legt sie fest, in dem der Extraktionsvorgang ausgeführt wird. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | Ruft Textsuchoptionen ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | Bindet PDF-Dokument aus Stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | PDF-Eingabedatei binden. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf.Document gebunden mit einer Fassade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | Extrahiert Anhänge aus einem PDF-Dokument. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | Extrahiert den Anhang in eine PDF-Datei nach Anhangsname. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | Bilder aus PDF-Datei extrahieren. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | Extrahiert Text aus einem PDF-Dokument mit Unicode-Codierung. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | Extrahiert Text aus einem PDF-Dokument unter Verwendung der angegebenen Kodierung. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | Speichert alle angehängten Dateien in Streams. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | Speichert Anhang in Datei. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | Ruft die Liste der Anhänge ab. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | Gibt eine Liste der Anhänge in der PDF-Datei zurück. Hinweis: ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es im Stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | Ruft das nächste Bild aus dem PDF-Dokument ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es im Stream mit dem angegebenen Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | Ruft das nächste Bild aus dem PDF-Dokument mit dem angegebenen Bildformat ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | Speichert den Text einer Seite im Stream. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | Speichert den Text einer Seite in einer Datei. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | Speichert Text im Stream. siehe auch:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | Speichert Text in Datei. siehe auch:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | Speichert Text im Stream. siehe auch:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | Prüft, ob mehr Bilder im PDF-Dokument zugänglich sind. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | Gibt an, ob weitere SMS empfangen werden können oder nicht. |

### Siehe auch

* class [Facade](../facade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
