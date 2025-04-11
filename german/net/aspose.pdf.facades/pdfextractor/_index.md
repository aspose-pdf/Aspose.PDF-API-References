---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfExtractor-Klasse. Klasse zum Extrahieren von Bildern und Text aus PDF-Dokumenten
type: docs
weight: 4450
url: /de/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor-Klasse

Klasse zum Extrahieren von Bildern und Text aus PDF-Dokumenten.

```csharp
public sealed class PdfExtractor : Facade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Initialisiert ein neues `PdfExtractor`-Objekt. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Initialisiert ein neues `PdfExtractor`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Gibt die Endseite im Seitenbereich zurück oder setzt sie, in dem die Extraktionsoperation durchgeführt wird. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Setzt den Modus für den Extraktionsprozess von Bildern. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Setzt den Modus für das Ergebnis der Textextraktion. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Ist wahr, wenn der Text hebräische oder arabische Symbole enthält. Dieser Fall muss besonders berücksichtigt werden, da sich die String-Funktionen in ihrem Verhalten ändern und den Text von rechts nach links verarbeiten (außer Zahlen und anderen Nicht-Textzeichen). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Gibt das Passwort der Eingabedatei zurück oder setzt es. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Setzt oder gibt die Auflösung für extrahierte Bilder zurück. Der Standardwert ist 150. Bilder mit höherem Auflösungswert sind klarer. Eine Erhöhung des Auflösungswerts führt jedoch zu einer Erhöhung der benötigten Zeit und des Speichers für die Extraktion von Bildern. Um ein klares Bild zu erhalten, reicht es normalerweise aus, die Auflösung auf 150 oder 300 zu setzen. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Gibt die Startseite im Seitenbereich zurück oder setzt sie, in dem die Extraktionsoperation durchgeführt wird. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Gibt die Textsuchoptionen zurück oder setzt sie. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Bindet das PDF-Dokument aus dem Stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Bindet die Eingabe-PDF-Datei. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Gibt das mit einer Fassade verbundene Aspose.Pdf.Document frei. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extrahiert Anhänge aus einem PDF-Dokument. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extrahiert einen Anhang zur PDF-Datei nach Anhängenamen. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extrahiert Bilder aus der PDF-Datei. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extrahiert Text aus einem PDF-Dokument unter Verwendung von Unicode-Codierung. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extrahiert Text aus einem PDF-Dokument unter Verwendung der angegebenen Codierung. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Speichert alle Anhangsdateien in Streams. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Speichert den Anhang in einer Datei. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Gibt die Liste der Anhänge zurück. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Gibt die Liste der Anhänge in der PDF-Datei zurück. Hinweis: ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es im Stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Ruft das nächste Bild aus dem PDF-Dokument ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es im Stream im angegebenen Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Ruft das nächste Bild aus dem PDF-Dokument im angegebenen Bildformat ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Speichert den Text einer Seite im Stream. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Speichert den Text einer Seite in einer Datei. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Speichert Text im Stream. siehe auch:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Speichert Text in einer Datei. siehe auch:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Speichert Text im Stream. siehe auch:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Überprüft, ob weitere Bilder im PDF-Dokument verfügbar sind. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Gibt an, ob weitere Texte abgerufen werden können oder nicht. |

### Siehe auch

* Klasse [Facade](../facade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)