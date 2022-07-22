---
title: PdfBookmarkEditor
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse zum Arbeiten mit den Lesezeichen von PDF-Dateien einschließlich Erstellen Ändern Exportieren Importieren und Löschen.
type: docs
weight: 2430
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class

Repräsentiert eine Klasse zum Arbeiten mit den Lesezeichen von PDF-Dateien, einschließlich Erstellen, Ändern, Exportieren, Importieren und Löschen.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor#constructor)() | Initialisiert neu[`PdfBookmarkEditor`](../pdfbookmarkeditor) Objekt. |
| [PdfBookmarkEditor](pdfbookmarkeditor#constructor_1)(Document) | Initialisiert neu[`PdfBookmarkEditor`](../pdfbookmarkeditor) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialisiert die Fassade. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf.Document gebunden mit einer Fassade. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage#createbookmarkofpage)(string, int) | Erstellt ein Lesezeichen für die angegebene Seite. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage#createbookmarkofpage_1)(string[], int[]) | Erstellt Lesezeichen für die angegebenen Seiten. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks#createbookmarks)() | Erstellt Lesezeichen für alle Seiten. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks#createbookmarks_1)(Bookmark) | Erstellt das angegebene Lesezeichen im Dokument. Die Methode kann zum Bilden einer verschachtelten Lesezeichenhierarchie verwendet werden. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks#createbookmarks_2)(Color, bool, bool) | Lesezeichen für alle Seiten mit angegebener Farbe und Stil erstellen (fett, kursiv). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks#deletebookmarks)() | Löscht alle Lesezeichen des PDF-Dokuments. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks#deletebookmarks_1)(string) | Löscht das Lesezeichen des PDF-Dokuments. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml#exportbookmarkstoxml)(Stream) | Exportiert Lesezeichen in den XML-Stream. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml#exportbookmarkstoxml_1)(string) | Exportiert Lesezeichen in eine XML-Datei. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks#extractbookmarks)() | Extrahiert Lesezeichen aller Ebenen aus dem Dokument. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks#extractbookmarks_1)(Bookmark) | Extrahiert die Kinder eines Lesezeichens mit einem Titel wie im angegebenen bookamrk. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks#extractbookmarks_2)(bool) | Extrahiert Lesezeichen aller Ebenen aus dem Dokument. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks#extractbookmarks_3)(string) | Extrahiert die Lesezeichen mit dem angegebenen Titel. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml#importbookmarkswithxml)(Stream) | Importiert Lesezeichen aus der XML-Datei in das Dokument. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml#importbookmarkswithxml_1)(string) | Importiert Lesezeichen aus der XML-Datei in das Dokument. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks)(string, string) | Ändert den Lesezeichentitel gemäß dem angegebenen Lesezeichentitel. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml)(string, string) | Exportiert Lesezeichen in eine HTML-Datei. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
