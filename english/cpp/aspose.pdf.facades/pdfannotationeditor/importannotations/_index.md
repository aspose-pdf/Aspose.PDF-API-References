---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations method
linktitle: ImportAnnotations
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations method. Imports annotations into document from array of another PDF document streams in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>) method


Imports annotations into document from array of another PDF document streams.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> annotFileStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | The array of streams of PDF documents that contain source annotations. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::ArrayPtr\<Annotations::AnnotationType\>) method


Imports the specified annotations into document from array of another PDF document streams.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> annotFileStream, System::ArrayPtr<Annotations::AnnotationType> annotType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | The array of streams of PDF documents that contain source annotations. |
| annotType | System::ArrayPtr\<Annotations::AnnotationType\> | The annotation types to be imported. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr\<System::String\>) method


Imports annotations into document from array of another PDF documents.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr<System::String> annotFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | System::ArrayPtr\<System::String\> | The array of paths of PDF documents that contain source annotations. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr\<System::String\>, System::ArrayPtr\<Annotations::AnnotationType\>) method


Imports the specified annotations into document from array of another PDF documents.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(System::ArrayPtr<System::String> annotFile, System::ArrayPtr<Annotations::AnnotationType> annotType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | System::ArrayPtr\<System::String\> | The array of paths of PDF documents that contain source annotations. |
| annotType | System::ArrayPtr\<Annotations::AnnotationType\> | The array of annotation types to be imported. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
