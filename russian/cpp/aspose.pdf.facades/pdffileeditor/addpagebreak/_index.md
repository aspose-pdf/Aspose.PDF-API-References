---
title: "Метод Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak"
linktitle: "AddPageBreak"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak. Добавляет разрывы страниц в страницы документа на C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/addpagebreak/
---
## PdfFileEditor::AddPageBreak(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Добавляет разрывы страниц в документ.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::SharedPtr<Document> &src, const System::SharedPtr<Document> &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::SharedPtr\<Document\>\& | Исходный документ. |
| dest | const System::SharedPtr\<Document\>\& | Документ назначения. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Массив объектов [PageBreak](../pagebreak/), описывающих места разрывов страниц. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Добавляет разрывы страниц в документ.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::SharedPtr<System::IO::Stream> &src, const System::SharedPtr<System::IO::Stream> &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::SharedPtr\<System::IO::Stream\>\& | Источник, содержащий исходный документ. |
| dest | const System::SharedPtr\<System::IO::Stream\>\& | Источник, где будет сохранён документ назначения. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Массив объектов [PageBreak](../pagebreak/), описывающих страницы и места, где будет добавлен разрыв страницы. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddPageBreak(const System::String\&, const System::String\&, const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\&) method


Добавляет разрывы страниц в документ.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::AddPageBreak(const System::String &src, const System::String &dest, const System::ArrayPtr<System::SharedPtr<PdfFileEditor::PageBreak>> &pageBreaks)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::String\& | Путь к исходному документу. |
| dest | const System::String\& | Путь к документу назначения. |
| pageBreaks | const System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>\& | Массив объектов [PageBreak](../pagebreak/), описывающих страницы и места, где будет добавлен разрыв страницы. |

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageBreak](../pagebreak/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
