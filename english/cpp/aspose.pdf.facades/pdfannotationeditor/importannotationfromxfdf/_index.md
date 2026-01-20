---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf method
linktitle: ImportAnnotationFromXfdf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf method. Imports all annotations from XFDF data stream in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## PdfAnnotationEditor::ImportAnnotationFromXfdf(System::SharedPtr\<System::IO::Stream\>) method


Imports all annotations from XFDF data stream.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(System::SharedPtr<System::IO::Stream> xfdfStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | System::SharedPtr\<System::IO::Stream\> | The input XFDF data stream. |

## Deprecated
Method is obsolete, please use ImportAnnotationsFromXfdf instead 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<Annotations::AnnotationType\>) method


Imports the specified annotations from XFDF data stream.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(System::SharedPtr<System::IO::Stream> xfdfStream, System::ArrayPtr<Annotations::AnnotationType> annotType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | System::SharedPtr\<System::IO::Stream\> | The input XFDF data stream. |
| annotType | System::ArrayPtr\<Annotations::AnnotationType\> | The array of annotation types to be imported. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(System::String) method


Imports all annotations from XFDF file.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(System::String xfdfFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | System::String | The input XFDF file. |

## Deprecated
Method is obsolete, please use ImportAnnotationsFromXfdf instead 

## See Also

* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(System::String, System::ArrayPtr\<Annotations::AnnotationType\>) method


Imports the specified annotations from XFDF file.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(System::String xfdfFile, System::ArrayPtr<Annotations::AnnotationType> annotType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | System::String | The input XFDF file. |
| annotType | System::ArrayPtr\<Annotations::AnnotationType\> | The annotations array to be imported. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
