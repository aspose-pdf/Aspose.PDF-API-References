---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfBookmarkEditor-Klasse. Stellt eine Klasse zum Arbeiten mit Lesezeichen in PDF-Dateien dar, einschließlich Erstellen, Ändern, Exportieren, Importieren und Löschen.
type: docs
weight: 4420
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor-Klasse

Stellt eine Klasse zum Arbeiten mit Lesezeichen in PDF-Dateien dar, einschließlich Erstellen, Ändern, Exportieren, Importieren und Löschen.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Initialisiert ein neues `PdfBookmarkEditor`-Objekt. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Initialisiert ein neues `PdfBookmarkEditor`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Gibt das mit einer Fassade verbundene Aspose.Pdf.Document frei. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Erstellt ein Lesezeichen für die angegebene Seite. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Erstellt Lesezeichen für die angegebenen Seiten. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Erstellt Lesezeichen für alle Seiten. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Erstellt das angegebene Lesezeichen im Dokument. Die Methode kann verwendet werden, um eine hierarchische Struktur von verschachtelten Lesezeichen zu bilden. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Erstellt Lesezeichen für alle Seiten mit der angegebenen Farbe und dem Stil (fett, kursiv). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Löscht alle Lesezeichen des PDF-Dokuments. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Löscht das Lesezeichen des PDF-Dokuments. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Exportiert Lesezeichen in einen XML-Stream. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Exportiert Lesezeichen in eine XML-Datei. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Extrahiert Lesezeichen aller Ebenen aus dem Dokument. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Extrahiert die Kinder eines Lesezeichens mit einem Titel wie im angegebenen Lesezeichen. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Extrahiert Lesezeichen aller Ebenen aus dem Dokument. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Extrahiert die Lesezeichen mit dem angegebenen Titel. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Importiert Lesezeichen aus einer XML-Datei in das Dokument. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Importiert Lesezeichen aus einer XML-Datei in das Dokument. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Ändert den Titel des Lesezeichens gemäß dem angegebenen Lesezeichentitel. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Exportiert Lesezeichen in eine HTML-Datei. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)