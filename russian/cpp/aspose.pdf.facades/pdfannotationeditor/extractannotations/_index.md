---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations метод"
linktitle: "ExtractAnnotations"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations метод. Получает список аннотаций указанных типов в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Получает список аннотаций указанных типов.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, const System::ArrayPtr<Annotations::AnnotationType> &annotTypes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| начало | int32_t | Начальная страница, с которой будут выбраны аннотации. |
| end | int32_t | Конечная страница, на которой будут выбраны аннотации. |
| annotTypes | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Массив необходимых типов аннотаций. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) method


Получает список аннотаций указанных типов.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, const System::ArrayPtr<System::String> &annotTypes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| начало | int32_t | Начальная страница, с которой будут выбраны аннотации. |
| end | int32_t | Конечная страница, на которой будут выбраны аннотации. |
| annotTypes | const System::ArrayPtr\<System::String\>\& | Массив необходимых типов аннотаций. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
