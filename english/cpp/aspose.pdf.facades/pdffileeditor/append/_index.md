---
title: Aspose::Pdf::Facades::PdfFileEditor::Append method
linktitle: Append
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::Append method. Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.facades/pdffileeditor/append/
---
## PdfFileEditor::Append(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<System::SharedPtr<System::IO::Stream>> portStreams, int32_t startPage, int32_t endPage, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input [Pdf](../../../aspose.pdf/) stream. |
| portStreams | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Documents to copy pages from. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) starts in portStreams documents. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) ends in portStreams documents . |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output [Pdf](../../../aspose.pdf/) stream. |

### ReturnValue

True for success, or false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Appends documents to source document and saves result into response object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<System::SharedPtr<System::IO::Stream>> portStreams, int32_t startPage, int32_t endPage, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream which contains source document. |
| portStreams | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Array of streams with documents to be appended. |
| startPage | int32_t | Start page of appended page. |
| endPage | int32_t | End page of appended pages. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where document will be saved. |

### ReturnValue

true if operation was successful.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> portStream, int32_t startPage, int32_t endPage, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input file Stream. |
| portStream | System::SharedPtr\<System::IO::Stream\> | Pages from [Pdf](../../../aspose.pdf/) file Stream. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) starts in portFile Stream. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) ends in portFile Stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output [Pdf](../../../aspose.pdf/) file Stream. |

### ReturnValue

True for success, or false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Appends documents to source document and saves result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(System::String inputFile, System::ArrayPtr<System::String> portFiles, int32_t startPage, int32_t endPage, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Name of file containing source document. |
| portFiles | System::ArrayPtr\<System::String\> | Array of file names containing appended documents. |
| startPage | int32_t | Start page of appended pages. |
| endPage | int32_t | End page of appended pages. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where document will be saved. |

### ReturnValue

true if operation was succeeded.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::String) method


Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(System::String inputFile, System::ArrayPtr<System::String> portFiles, int32_t startPage, int32_t endPage, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input [Pdf](../../../aspose.pdf/) file. |
| portFiles | System::ArrayPtr\<System::String\> | Documents to copy pages from. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) starts in portFiles documents. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) ends in portFiles documents . |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) document. |

### ReturnValue

True if operation was succeeded.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(System::String, System::String, int32_t, int32_t, System::String) method


Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(System::String inputFile, System::String portFile, int32_t startPage, int32_t endPage, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input [Pdf](../../../aspose.pdf/) file. |
| portFile | System::String | Pages from [Pdf](../../../aspose.pdf/) file. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) starts in portFile. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) ends in portFile. |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) document. |

### ReturnValue

True if operation was succeeded.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
