---
title: Aspose::Pdf::Facades::PdfFileEditor::TryExtract method
linktitle: TryExtract
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryExtract method. Extracts pages specified by number array, saves as a new Pdf file in C++.'
type: docs
weight: 6500
url: /cpp/aspose.pdf.facades/pdffileeditor/tryextract/
---
## PdfFileEditor::TryExtract(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) method


Extracts pages specified by number array, saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input file Stream. |
| pageNumber | System::ArrayPtr\<int32_t\> | Index of page out of the input file. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output file stream. |

### ReturnValue

True for success, or false.
## Remarks



The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Extracts specified pages form source file and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of source document. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers which will be extracted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(System::String, int32_t, int32_t, System::String) method


Extracts pages from input file,saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(System::String inputFile, int32_t startPage, int32_t endPage, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input [Pdf](../../../aspose.pdf/) file path. |
| startPage | int32_t | Start page number. |
| endPage | int32_t | End page number. |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) file path. |

### ReturnValue

True for success, or false.
## Remarks



The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Extracts specified pages from source file and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(System::String inputFile, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file path. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers which will be extracted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(System::String, System::ArrayPtr\<int32_t\>, System::String) method


Extracts pages specified by number array, saves as a new PDF file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(System::String inputFile, System::ArrayPtr<int32_t> pageNumber, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input file path. |
| pageNumber | System::ArrayPtr\<int32_t\> | Index of page out of the input file. |
| outputFile | System::String | Output file path. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails. 

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
