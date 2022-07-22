---
title: PdfAnnotationEditor
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse für die Arbeit mit PDF-Dokumentanmerkungen Kommentaren.
type: docs
weight: 2420
url: /de/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Repräsentiert eine Klasse für die Arbeit mit PDF-Dokumentanmerkungen (Kommentaren).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | Initialisiert neu[`PdfAnnotationEditor`](../pdfannotationeditor) Objekt. |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | Initialisiert neu[`PdfAnnotationEditor`](../pdfannotationeditor) Objekt auf Basis der*document* . |

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
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | Löscht die Anmerkung mit dem angegebenen Anmerkungsnamen. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | Löscht alle Anmerkungen im Dokument. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | Löscht alle Anmerkungen des angegebenen Typs im Dokument. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | Exportiert Anmerkungen in den Stream. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exportiert den Inhalt der angegebenen Anmerkungstypen in XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exportiert den Inhalt der angegebenen Anmerkungstypen in XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | Ruft die Liste der Anmerkungen der angegebenen Typen ab. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | Ruft die Liste der Anmerkungen der angegebenen Typen ab. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | Flacht alle Anmerkungen im Dokument ab. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | Flacht alle Anmerkungen im Dokument ab. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | Flacht die Anmerkungen der angegebenen Typen ab. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importiert die angegebenen Anmerkungen aus dem XFDF-Datenstrom. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | Importiert die angegebenen Anmerkungen aus der XFDF-Datei. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | Importiert Anmerkungen in das Dokument aus einem Array anderer PDF-Dokument-Streams. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | Importiert Anmerkungen aus einem Array anderer PDF-Dokumente in das Dokument. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | Importiert die angegebenen Anmerkungen aus dem Array anderer PDF-Dokumentstreams in das Dokument. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | Importiert die angegebenen Anmerkungen aus dem Array anderer PDF-Dokumente in das Dokument. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importiert alle Anmerkungen aus dem XFDF-Datenstrom. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importiert alle Anmerkungen aus der XFDF-Datei. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | Ändert die Anmerkungen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Änderung der nächsten Anmerkungseigenschaften: Geändert, Titel, Inhalt, Farbe, Betreff und Öffnen. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | Ändert den Autor von Anmerkungen im angegebenen Seitenbereich. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | Schwärzt den Bereich auf der angegebenen Seite. Alle Inhalte werden entfernt. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
