---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations method
linktitle: FlatteningAnnotations
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations method. Flattens all annotations in the document in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## PdfAnnotationEditor::FlatteningAnnotations() method


Flattens all annotations in the document.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations()
```

## See Also

* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::FlatteningAnnotations(int32_t, int32_t, System::ArrayPtr\<Annotations::AnnotationType\>) method


Flattens the annotations of the specified types.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations(int32_t start, int32_t end, System::ArrayPtr<Annotations::AnnotationType> annotType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | int32_t | The start page. |
| end | int32_t | Then end page. |
| annotType | System::ArrayPtr\<Annotations::AnnotationType\> | The annotation types should be flattened. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::FlatteningAnnotations(System::SharedPtr\<Forms::Form::FlattenSettings\>) method


Flattens all annotations in the document.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations(System::SharedPtr<Forms::Form::FlattenSettings> flattenSettings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| flattenSettings | System::SharedPtr\<Forms::Form::FlattenSettings\> | Specifies modes of flattening. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FlattenSettings](../../../aspose.pdf.forms/form/flattensettings/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
