---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf метод"
linktitle: "ImportAnnotationFromXfdf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf метод. Импортирует все аннотации из потока данных XFDF в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr\<System::IO::Stream\>\&) method


Импортирует все аннотации из потока данных XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr<System::IO::Stream> &xfdfStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток данных XFDF. |

## Deprecated
Метод устарел, пожалуйста, используйте ImportAnnotationsFromXfdf вместо этого

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Импортирует указанные аннотации из потока данных XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr<System::IO::Stream> &xfdfStream, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток данных XFDF. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Массив типов аннотаций для импорта. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String\&) method


Импортирует все аннотации из файла XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String &xfdfFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfFile | const System::String\& | Входной файл XFDF. |

## Deprecated
Метод устарел, пожалуйста, используйте ImportAnnotationsFromXfdf вместо этого

## См. также

* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Импортирует указанные аннотации из файла XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String &xfdfFile, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfFile | const System::String\& | Входной файл XFDF. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Массив аннотаций для импорта. |

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
