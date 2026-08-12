---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations метод"
linktitle: "ImportAnnotations"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations метод. Импортирует аннотации в документ из массива потоков других PDF‑документов в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) method


Импортирует аннотации в документ из массива потоков других PDF‑документов.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &annotFileStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFileStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Массив потоков PDF‑документов, содержащих исходные аннотации. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Импортирует указанные аннотации в документ из массива потоков других PDF‑документов.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &annotFileStream, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFileStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Массив потоков PDF‑документов, содержащих исходные аннотации. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Типы аннотаций для импорта. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::String\>\&) method


Импортирует аннотации в документ из массива других PDF‑документов.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::String> &annotFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFile | const System::ArrayPtr\<System::String\>\& | Массив путей к PDF‑документам, содержащим исходные аннотации. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Импортирует указанные аннотации в документ из массива других PDF‑документов.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::String> &annotFile, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFile | const System::ArrayPtr\<System::String\>\& | Массив путей к PDF‑документам, содержащим исходные аннотации. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Массив типов аннотаций для импорта. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
