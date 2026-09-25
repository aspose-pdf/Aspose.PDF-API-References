---
title: "PdfAnnotationEditor Class"
linktitle: "PdfAnnotationEditor"
articleTitle: "PdfAnnotationEditor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfAnnotationEditor class. Represents a class for work with PDF document annotations (comments)."
type: docs
weight: 300
url: "/net/aspose.pdf.facades/pdfannotationeditor/"
keywords: "PdfAnnotationEditor, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfAnnotationEditor class

Represents a class for work with PDF document annotations (comments).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAnnotationEditor](./pdfannotationeditor/#constructor) | Initializes new [`PdfAnnotationEditor`](../../aspose.pdf.facades/pdfannotationeditor/) object. |
| [PdfAnnotationEditor](./pdfannotationeditor/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfAnnotationEditor`](../../aspose.pdf.facades/pdfannotationeditor/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string*) | Initializes the facade. *(Inherited from Facade)* |
| [Close](../../aspose.pdf.facades/facade/close/) | Disposes Aspose.Pdf.Document bound with a facade. *(Inherited from Facade)* |
| [DeleteAnnotation](./deleteannotation/)(*string*) | Deletes the annotation with specified annotation name. |
| [DeleteAnnotations](./deleteannotations/) | Deletes all annotations in the document. |
| [DeleteAnnotations](./deleteannotations/)(*string*) | Deletes all annotations of the specified type in the document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(*Stream*) | Exports annotations to stream. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(*Stream, int, int, string[]*) | Exports the content of the specified annotation types into XFDF. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(*Stream, int, int, AnnotationType[]*) | Exports the content of the specified annotations types into XFDF. |
| [ExtractAnnotations](./extractannotations/)(*int, int, string[]*) | Gets the list of annotations of the specified types. |
| [ExtractAnnotations](./extractannotations/)(*int, int, AnnotationType[]*) | Gets the list of annotations of the specified types. |
| [FlatteningAnnotations](./flatteningannotations/) | Flattens all annotations in the document. |
| [FlatteningAnnotations](./flatteningannotations/)(*FlattenSettings*) |  |
| [FlatteningAnnotations](./flatteningannotations/)(*int, int, AnnotationType[]*) | Flattens the annotations of the specified types. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(*string*) | Imports all annotations from XFDF file. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(*Stream*) | Imports all annotations from XFDF data stream. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(*string, AnnotationType[]*) | Imports the specified annotations from XFDF file. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(*Stream, AnnotationType[]*) | Imports the specified annotations from XFDF data stream. |
| [ImportAnnotations](./importannotations/)(*string[]*) | Imports annotations into document from array of another PDF documents. |
| [ImportAnnotations](./importannotations/)(*Stream[]*) | Imports annotations into document from array of another PDF document streams. |
| [ImportAnnotations](./importannotations/)(*string[], AnnotationType[]*) | Imports the specified annotations into document from array of another PDF documents. |
| [ImportAnnotations](./importannotations/)(*Stream[], AnnotationType[]*) | Imports the specified annotations into document from array of another PDF document streams. |
| [ImportAnnotationsFromFdf](./importannotationsfromfdf/)(*string*) | Imports all annotations from FDF file. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(*string*) | Imports all annotations from XFDF file. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(*Stream*) | Imports all annotations from XFDF data stream. |
| [ModifyAnnotations](./modifyannotations/)(*int, int, Annotation*) | Modifies the annotations of the specifed type on the specified page range. |
| [ModifyAnnotations](./modifyannotations/)(*int, int, Enum, Annotation*) | Modifies the annotations of the specifed type on the specified page range. |
| [ModifyAnnotationsAuthor](./modifyannotationsauthor/)(*int, int, string, string*) | Modifies the author of annotations on the specified page range. |
| [RedactArea](./redactarea/)(*int, Rectangle, Color*) | Redacts area on the specified page. All contents is removed. |
| [Save](../../aspose.pdf.facades/saveablefacade/save/)(*string*) | Saves the PDF document to the specified file. *(Inherited from SaveableFacade)* |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

