---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks метод"
linktitle: "SplitToBulks"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks метод. Разделяет файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными в C++."
type: docs
weight: 5900
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## PdfFileEditor::SplitToBulks(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Разделяет файл [Pdf](../../../aspose.pdf/) на несколько документов. Документы могут быть одностраничными или многостраничными.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток PDF. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | Начальная и конечная страницы каждого документа. |

### ReturnValue

Выходные потоки PDF, каждый поток буферизует PDF‑документ.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToBulks(const System::String\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Разделяет файл [Pdf](../../../aspose.pdf/) на несколько документов. Документы могут быть одностраничными или многостраничными.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::String &inputFile, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл PDF. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | Массив, содержащий массив элементов double, представляющих начальные и конечные страницы документа. |

### ReturnValue

Выходные потоки PDF, каждый поток буферизует PDF‑документ.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
