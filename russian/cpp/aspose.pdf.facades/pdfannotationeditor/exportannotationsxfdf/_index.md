---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf метод"
linktitle: "ExportAnnotationsXfdf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf метод. Экспортирует содержимое указанных типов аннотаций в XFDF в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Экспортирует содержимое указанных типов аннотаций в XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr<System::IO::Stream> &xmlOutputStream, int32_t start, int32_t end, const System::ArrayPtr<Annotations::AnnotationType> &annotTypes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlOutputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток XFDF. |
| начало | int32_t | Начальная страница, с которой аннотации документа будут экспортированы. |
| end | int32_t | Конечная страница, до которой аннотации документа будут экспортированы. |
| annotTypes | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Массив типов аннотаций, которые необходимо экспортировать. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) method


Экспортирует содержимое указанных типов аннотаций в XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr<System::IO::Stream> &xmlOutputStream, int32_t start, int32_t end, const System::ArrayPtr<System::String> &annotTypes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlOutputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток XFDF. |
| начало | int32_t | Начальная страница, с которой аннотации документа будут экспортированы. |
| end | int32_t | Конечная страница, до которой аннотации документа будут экспортированы. |
| annotTypes | const System::ArrayPtr\<System::String\>\& | Массив типов аннотаций, которые необходимо экспортировать. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
