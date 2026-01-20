---
title: Aspose::Pdf::Facades::PdfFileEditor::SplitToPages method
linktitle: SplitToPages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::SplitToPages method. Splits the Pdf file into single-page documents in C++.'
type: docs
weight: 6100
url: /cpp/aspose.pdf.facades/pdffileeditor/splittopages/
---
## PdfFileEditor::SplitToPages(System::SharedPtr\<System::IO::Stream\>) method


Splits the [Pdf](../../../aspose.pdf/) file into single-page documents.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(System::SharedPtr<System::IO::Stream> inputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input [Pdf](../../../aspose.pdf/) stream. |

### ReturnValue

Array of memory streams which contain pages of the document.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(System::SharedPtr\<System::IO::Stream\>, System::String) method


Split the [Pdf](../../../aspose.pdf/) file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(System::SharedPtr<System::IO::Stream> inputStream, System::String fileNameTemplate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of the soruce document. |
| fileNameTemplate | System::String | Template of resultant file name. Must contain NUM% which is replaced with page number. For example, if c:/dir/pageNUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(System::String) method


Splits the PDF file into single-page documents.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(System::String inputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input PDF file name. |

### ReturnValue

Output PDF streams, each stream buffers a single-page PDF document.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(System::String, System::String) method


Split the [Pdf](../../../aspose.pdf/) file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(System::String inputFile, System::String fileNameTemplate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input file name. |
| fileNameTemplate | System::String | Template of resultant file name. Must contain NUM% which is replaced with page number. For example, if c:/dir/pageNUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
