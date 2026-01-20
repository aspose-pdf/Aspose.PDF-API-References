---
title: Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet method
linktitle: TryMakeBooklet
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet method. Make booklet from PDF file and stores it into HttpResponse in C++.'
type: docs
weight: 6700
url: /cpp/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## PdfFileEditor::TryMakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Make booklet from PDF file and stores it into HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input document stream. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size. |
| leftPages | System::ArrayPtr\<int32_t\> | Array of page numbers which will be placed in left. |
| rightPages | System::ArrayPtr\<int32_t\> | Array of page numbers which will b eplaced in right. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes booklet from source file and stores result into HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input document stream. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size in output file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Respose object where resut will be saved. |

### ReturnValue

true if booklet was built successfully.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Makes booklet from the InputStream to outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input pdf stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes customized booklet from the firstInputStream to outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | The input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) method


Makes booklet from the input stream and save result into output stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input PDF stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes booklet from the firstInputStream to outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | The input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes booklet from source file and stores result into HttpResponse objects.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::String inputFile, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file path. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size. |
| leftPages | System::ArrayPtr\<int32_t\> | Aray of page numbers to be placed in left. |
| rightPages | System::ArrayPtr\<int32_t\> | Array of page numbers to be placed in right. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes booklet from source file and stores result into HttpResponse objects.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::String inputFile, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file path. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size in output file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

True if operation is succeeded.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::String, System::String) method


Makes booklet from the input file to output file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::String inputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::String, System::String, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes customized booklet from the firstInputFile to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::String inputFile, System::String outputFile, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | The input file. |
| outputFile | System::String | Output pdf file path and name. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages of the booklet. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages of the booklet. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::String, System::String, System::SharedPtr\<PageSize\>) method


Makes booklet from the inputFile to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::String inputFile, System::String outputFile, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

True if operation is succeeded.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(System::String, System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes customized booklet from the firstInputFile to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(System::String inputFile, System::String outputFile, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | The input file. |
| outputFile | System::String | Output pdf file path and name. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
