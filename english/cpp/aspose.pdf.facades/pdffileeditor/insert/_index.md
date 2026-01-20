---
title: Aspose::Pdf::Facades::PdfFileEditor::Insert method
linktitle: Insert
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::Insert method. Inserts pages from an other file into the input Pdf file in C++.'
type: docs
weight: 3200
url: /cpp/aspose.pdf.facades/pdffileeditor/insert/
---
## PdfFileEditor::Insert(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Inserts pages from an other file into the input [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(System::SharedPtr<System::IO::Stream> inputStream, int32_t insertLocation, System::SharedPtr<System::IO::Stream> portStream, int32_t startPage, int32_t endPage, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input Stream of [Pdf](../../../aspose.pdf/) file. |
| insertLocation | int32_t | Insert position in input file. |
| portStream | System::SharedPtr\<System::IO::Stream\> | Stream of [Pdf](../../../aspose.pdf/) file for pages. |
| startPage | int32_t | From which page to start. |
| endPage | int32_t | To which page to end. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output Stream. |

### ReturnValue

True for success, or false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) method


Inserts pages from an other file into the input [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(System::SharedPtr<System::IO::Stream> inputStream, int32_t insertLocation, System::SharedPtr<System::IO::Stream> portStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input Stream of [Pdf](../../../aspose.pdf/) file. |
| insertLocation | int32_t | Insert position in input file. |
| portStream | System::SharedPtr\<System::IO::Stream\> | Stream of [Pdf](../../../aspose.pdf/) file for pages. |
| pageNumber | System::ArrayPtr\<int32_t\> | The page number of the ported in portFile. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output Stream. |

### ReturnValue

True if operation was succeeded.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Inserts document into other document and stores result into response object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(System::SharedPtr<System::IO::Stream> inputStream, int32_t insertLocation, System::SharedPtr<System::IO::Stream> portStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream with source document |
| insertLocation | int32_t | Location where other document will be inserted. |
| portStream | System::SharedPtr\<System::IO::Stream\> | [Document](../../../aspose.pdf/document/) to be inserted. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers in second document which will be inserted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where result will be stored. |

### ReturnValue

True if operation was succeeded.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(System::String, int32_t, System::String, int32_t, int32_t, System::String) method


Inserts pages from an other file into the [Pdf](../../../aspose.pdf/) file at a position.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(System::String inputFile, int32_t insertLocation, System::String portFile, int32_t startPage, int32_t endPage, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input [Pdf](../../../aspose.pdf/) file. |
| insertLocation | int32_t | Position in input file. |
| portFile | System::String | The porting [Pdf](../../../aspose.pdf/) file. |
| startPage | int32_t | Start position in portFile. |
| endPage | int32_t | End position in portFile. |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) file. |

### ReturnValue

True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Inserts contents of file into source file and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(System::String inputFile, int32_t insertLocation, System::String portFile, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file name. |
| insertLocation | int32_t | [Page](../../../aspose.pdf/page/) number where second file will be inserted. |
| portFile | System::String | Path to file which will be inserted. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers in source file wihich will be inserted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where result will be stored. |

### ReturnValue

true of inserting was successful.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::String) method


Inserts pages from an other file into the input [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(System::String inputFile, int32_t insertLocation, System::String portFile, System::ArrayPtr<int32_t> pageNumber, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input [Pdf](../../../aspose.pdf/) file. |
| insertLocation | int32_t | Insert position in input file. |
| portFile | System::String | Pages from the [Pdf](../../../aspose.pdf/) file. |
| pageNumber | System::ArrayPtr\<int32_t\> | The page number of the ported in portFile. |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) file. |

### ReturnValue

True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
