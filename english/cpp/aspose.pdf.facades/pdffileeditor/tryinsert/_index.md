---
title: Aspose::Pdf::Facades::PdfFileEditor::TryInsert method
linktitle: TryInsert
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryInsert method. Inserts pages from an other file into the input Pdf file in C++.'
type: docs
weight: 6600
url: /cpp/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## PdfFileEditor::TryInsert(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) method


Inserts pages from an other file into the input [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(System::SharedPtr<System::IO::Stream> inputStream, int32_t insertLocation, System::SharedPtr<System::IO::Stream> portStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input Stream of [Pdf](../../../aspose.pdf/) file. |
| insertLocation | int32_t | Insert position in input file. |
| portStream | System::SharedPtr\<System::IO::Stream\> | Stream of [Pdf](../../../aspose.pdf/) file for pages. |
| pageNumber | System::ArrayPtr\<int32_t\> | The page number of the ported in portFile. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output Stream. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryInsert(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Inserts document into other document and stores result into response object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(System::SharedPtr<System::IO::Stream> inputStream, int32_t insertLocation, System::SharedPtr<System::IO::Stream> portStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream with source document |
| insertLocation | int32_t | Location where other document will be inserted. |
| portStream | System::SharedPtr\<System::IO::Stream\> | [Document](../../../aspose.pdf/document/) to be inserted. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers in second document which will be inserted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryInsert(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Inserts contents of file into source file and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(System::String inputFile, int32_t insertLocation, System::String portFile, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file name. |
| insertLocation | int32_t | [Page](../../../aspose.pdf/page/) number where second file will be inserted. |
| portFile | System::String | Path to file which will be inserted. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers in source file wihich will be inserted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryInsert(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::String) method


Inserts pages from an other file into the input [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(System::String inputFile, int32_t insertLocation, System::String portFile, System::ArrayPtr<int32_t> pageNumber, System::String outputFile)
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
## Remarks



The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
