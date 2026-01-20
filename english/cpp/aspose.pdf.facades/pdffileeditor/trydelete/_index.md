---
title: Aspose::Pdf::Facades::PdfFileEditor::TryDelete method
linktitle: TryDelete
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryDelete method. Deletes pages specified by number array from input file, saves as a new Pdf file in C++.'
type: docs
weight: 6400
url: /cpp/aspose.pdf.facades/pdffileeditor/trydelete/
---
## PdfFileEditor::TryDelete(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) method


Deletes pages specified by number array from input file, saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input file Stream. |
| pageNumber | System::ArrayPtr\<int32_t\> | Index of page out of the input file. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output file stream. |

### ReturnValue

True for success, or false.
## Remarks



The TryDelete method is like the Delete method, except the TryDelete method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Deletes specified pages from document and saves result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Source document stream. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers which will be deleted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryDelete method is like the Delete method, except the TryDelete method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Deletes specified pages from document and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(System::String inputFile, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Path of source file. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers which must be deleted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where result document will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryDelete method is like the Delete method, except the TryDelete method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(System::String, System::ArrayPtr\<int32_t\>, System::String) method


Deletes pages specified by number array from input file, saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(System::String inputFile, System::ArrayPtr<int32_t> pageNumber, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input file path. |
| pageNumber | System::ArrayPtr\<int32_t\> | Index of page out of the input file. |
| outputFile | System::String | Output file path. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryDelete method is like the Delete method, except the TryDelete method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
