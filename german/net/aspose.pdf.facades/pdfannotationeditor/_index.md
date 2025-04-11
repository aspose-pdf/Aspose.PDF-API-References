---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfAnnotationEditor-Klasse. Stellt eine Klasse für die Arbeit mit PDF-Dokumentannotationskommentaren dar
type: docs
weight: 4410
url: /de/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor-Klasse

Stellt eine Klasse für die Arbeit mit PDF-Dokumentannotationskommentaren dar.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Initialisiert ein neues `PdfAnnotationEditor`-Objekt. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Initialisiert ein neues `PdfAnnotationEditor`-Objekt auf Basis des *Dokuments*. |

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
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Löscht die Annotation mit dem angegebenen Annotationsnamen. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Löscht alle Annotationen im Dokument. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Löscht alle Annotationen des angegebenen Typs im Dokument. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Exportiert Annotationen in einen Stream. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exportiert den Inhalt der angegebenen Annotationsarten in XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exportiert den Inhalt der angegebenen Annotationsarten in XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Gibt die Liste der Annotationen der angegebenen Typen zurück. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Gibt die Liste der Annotationen der angegebenen Typen zurück. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Flacht alle Annotationen im Dokument ab. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Flacht alle Annotationen im Dokument ab. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Flacht die Annotationen der angegebenen Typen ab. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importiert die angegebenen Annotationen aus dem XFDF-Datenstream. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Importiert die angegebenen Annotationen aus der XFDF-Datei. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Importiert Annotationen in das Dokument aus einem Array von Streams anderer PDF-Dokumente. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Importiert Annotationen in das Dokument aus einem Array anderer PDF-Dokumente. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Importiert die angegebenen Annotationen in das Dokument aus einem Array von Streams anderer PDF-Dokumente. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Importiert die angegebenen Annotationen in das Dokument aus einem Array anderer PDF-Dokumente. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Importiert alle Annotationen aus der FDF-Datei. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importiert alle Annotationen aus dem XFDF-Datenstream. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importiert alle Annotationen aus der XFDF-Datei. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Modifiziert die Annotationen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Modifikation der folgenden Annotationsattribute: Modified, Title, Contents, Color, Subject und Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Modifiziert den Autor der Annotationen im angegebenen Seitenbereich. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Schwärzt einen Bereich auf der angegebenen Seite. Alle Inhalte werden entfernt. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)