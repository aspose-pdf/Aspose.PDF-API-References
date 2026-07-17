---
title: Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks method
linktitle: SplitToBulks
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks method. Splits the Pdf file into several documents.The documents can be single-page or multi-pages in C++.'
type: docs
weight: 5900
url: /cpp/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## PdfFileEditor::SplitToBulks(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Splits the [Pdf](../../../aspose.pdf/) file into several documents.The documents can be single-page or multi-pages.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input PDF stream. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | The start page and the end page of each document. |

### ReturnValue

Output PDF streams, each stream buffers a PDF document.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToBulks(const System::String\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Splits the [Pdf](../../../aspose.pdf/) file into several documents.The documents can be single-page or multi-pages.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::String &inputFile, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Input PDF file. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | Array which contains array of double elements, which is start and end pages of document. |

### ReturnValue

Output PDF streams, each stream buffers a PDF document.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
