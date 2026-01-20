---
title: Aspose::Pdf::Facades::PdfAnnotationEditor class
linktitle: PdfAnnotationEditor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor class. Represents a class for work with PDF document annotations (comments) in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class


Represents a class for work with PDF document annotations (comments).

```cpp
class PdfAnnotationEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [DeleteAnnotation](./deleteannotation/)(System::String) | Deletes the annotation with specified annotation name. |
| [DeleteAnnotations](./deleteannotations/)() | Deletes all annotations in the document. |
| [DeleteAnnotations](./deleteannotations/)(System::String) | Deletes all annotations of the specified type in the document. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(System::SharedPtr\<System::IO::Stream\>) | Exports annotations to stream. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::ArrayPtr\<System::String\>) | Exports the content of the specified annotation types into XFDF. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::ArrayPtr\<Annotations::AnnotationType\>) | Exports the content of the specified annotations types into XFDF. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, System::ArrayPtr\<System::String\>) | Gets the list of annotations of the specified types. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, System::ArrayPtr\<Annotations::AnnotationType\>) | Gets the list of annotations of the specified types. |
| [FlatteningAnnotations](./flatteningannotations/)() | Flattens all annotations in the document. |
| [FlatteningAnnotations](./flatteningannotations/)(System::SharedPtr\<Forms::Form::FlattenSettings\>) | Flattens all annotations in the document. |
| [FlatteningAnnotations](./flatteningannotations/)(int32_t, int32_t, System::ArrayPtr\<Annotations::AnnotationType\>) | Flattens the annotations of the specified types. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(System::String) | Imports all annotations from XFDF file. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(System::String, System::ArrayPtr\<Annotations::AnnotationType\>) | Imports the specified annotations from XFDF file. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<Annotations::AnnotationType\>) | Imports the specified annotations from XFDF data stream. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(System::SharedPtr\<System::IO::Stream\>) | Imports all annotations from XFDF data stream. |
| [ImportAnnotations](./importannotations/)(System::ArrayPtr\<System::String\>, System::ArrayPtr\<Annotations::AnnotationType\>) | Imports the specified annotations into document from array of another PDF documents. |
| [ImportAnnotations](./importannotations/)(System::ArrayPtr\<System::String\>) | Imports annotations into document from array of another PDF documents. |
| [ImportAnnotations](./importannotations/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::ArrayPtr\<Annotations::AnnotationType\>) | Imports the specified annotations into document from array of another PDF document streams. |
| [ImportAnnotations](./importannotations/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>) | Imports annotations into document from array of another PDF document streams. |
| [ImportAnnotationsFromFdf](./importannotationsfromfdf/)(System::String) | Imports all annotations from FDF file. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(System::String) | Imports all annotations from XFDF file. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(System::SharedPtr\<System::IO::Stream\>) | Imports all annotations from XFDF data stream. |
| [ModifyAnnotations](./modifyannotations/)(int32_t, int32_t, System::SharedPtr\<Annotations::Annotation\>) | Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, [Color](../../aspose.pdf/color/), Subject and Open. |
| [ModifyAnnotationsAuthor](./modifyannotationsauthor/)(int32_t, int32_t, System::String, System::String) | Modifies the author of annotations on the specified page range. |
| [PdfAnnotationEditor](./pdfannotationeditor/)() | Initializes new [PdfAnnotationEditor](./) object. |
| [PdfAnnotationEditor](./pdfannotationeditor/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfAnnotationEditor](./) object on base of the *document* . |
| [RedactArea](./redactarea/)(int32_t, System::SharedPtr\<Rectangle\>, System::Drawing::Color) | Redacts area on the specified page. All contents is removed. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
