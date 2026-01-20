---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf method
linktitle: ExportAnnotationsXfdf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf method. Exports the content of the specified annotations types into XFDF in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::ArrayPtr\<Annotations::AnnotationType\>) method


Exports the content of the specified annotations types into XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr<System::IO::Stream> xmlOutputStream, int32_t start, int32_t end, System::ArrayPtr<Annotations::AnnotationType> annotTypes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlOutputStream | System::SharedPtr\<System::IO::Stream\> | The output XFDF stream. |
| start | int32_t | Start page from which the annotations of the document will be exported. |
| end | int32_t | End page to which the annotations of the document will be exported. |
| annotTypes | System::ArrayPtr\<Annotations::AnnotationType\> | The array of annotation types need be exported. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::ArrayPtr\<System::String\>) method


Exports the content of the specified annotation types into XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr<System::IO::Stream> xmlOutputStream, int32_t start, int32_t end, System::ArrayPtr<System::String> annotTypes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlOutputStream | System::SharedPtr\<System::IO::Stream\> | The output XFDF stream. |
| start | int32_t | Start page from which the annotations of the document will be exported. |
| end | int32_t | End page to which the annotations of the document will be exported. |
| annotTypes | System::ArrayPtr\<System::String\> | The array of annotation types need be exported. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
