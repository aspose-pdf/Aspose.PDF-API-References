---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations метод"
linktitle: "FlatteningAnnotations"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations метод. Уплощает все аннотации в документе в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## PdfAnnotationEditor::FlatteningAnnotations() method


Преобразует все аннотации в документе в плоские.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations()
```

## См. также

* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::FlatteningAnnotations(const System::SharedPtr\<Forms::Form::FlattenSettings\>\&) method


Преобразует все аннотации в документе в плоские.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations(const System::SharedPtr<Forms::Form::FlattenSettings> &flattenSettings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| flattenSettings | const System::SharedPtr\<Forms::Form::FlattenSettings\>\& | Указывает режимы уплощения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FlattenSettings](../../../aspose.pdf.forms/form/flattensettings/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::FlatteningAnnotations(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Уплощает аннотации указанных типов.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations(int32_t start, int32_t end, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| начало | int32_t | Начальная страница. |
| end | int32_t | Затем конечная страница. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Типы аннотаций должны быть уплощены. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
