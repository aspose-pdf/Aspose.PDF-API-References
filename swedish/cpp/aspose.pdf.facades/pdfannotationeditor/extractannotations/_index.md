---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations metod"
linktitle: "ExtractAnnotations"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations metod. Hämtar listan över annoteringar av de angivna typerna i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Hämtar listan över anteckningar av de angivna typerna.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, const System::ArrayPtr<Annotations::AnnotationType> &annotTypes)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | int32_t | Startsida från vilken annoteringarna kommer att väljas. |
| end | int32_t | Slutsida till vilken annoteringarna kommer att väljas. |
| annotTypes | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Arrayen med nödvändiga annoteringstyper. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) method


Hämtar listan över anteckningar av de angivna typerna.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, const System::ArrayPtr<System::String> &annotTypes)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | int32_t | Startsida från vilken annoteringarna kommer att väljas. |
| end | int32_t | Slutsida till vilken annoteringarna kommer att väljas. |
| annotTypes | const System::ArrayPtr\<System::String\>\& | Arrayen med nödvändiga annoteringstyper. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
