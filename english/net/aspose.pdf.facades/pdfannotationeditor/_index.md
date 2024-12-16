---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfAnnotationEditor class. Represents a class for work with PDF document annotations comments
type: docs
weight: 4380
url: /net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Represents a class for work with PDF document annotations (comments).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Initializes new `PdfAnnotationEditor` object. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Initializes new `PdfAnnotationEditor` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Disposes Aspose.Pdf.Document bound with a facade. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Deletes the annotation with specified annotation name. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Deletes all annotations in the document. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Deletes all annotations of the specified type in the document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Exports annotations to stream. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exports the content of the specified annotations types into XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exports the content of the specified annotation types into XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Gets the list of annotations of the specified types. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Gets the list of annotations of the specified types. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Flattens all annotations in the document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Flattens all annotations in the document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Flattens the annotations of the specified types. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Imports the specified annotations from XFDF data stream. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Imports the specified annotations from XFDF file. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Imports annotations into document from array of another PDF document streams. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Imports annotations into document from array of another PDF documents. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Imports the specified annotations into document from array of another PDF document streams. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Imports the specified annotations into document from array of another PDF documents. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Imports all annotations from FDF file. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Imports all annotations from XFDF data stream. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Imports all annotations from XFDF file. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Modifies the author of annotations on the specified page range. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Redacts area on the specified page. All contents is removed. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Saves the PDF document to the specified stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Saves the PDF document to the specified file. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


