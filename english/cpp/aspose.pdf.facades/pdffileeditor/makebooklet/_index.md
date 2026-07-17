---
title: Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet method
linktitle: MakeBooklet
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet method. Make booklet from PDF file and stores it into HttpResponse in C++.'
type: docs
weight: 3300
url: /cpp/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Make booklet from PDF file and stores it into HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input document stream. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Desired page size. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Array of page numbers which will be placed in left. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Array of page numbers which will b eplaced in right. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object. |

### ReturnValue

True if operation was succeeded.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Makes booklet from source file and stores result into HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input document stream. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Desired page size in output file. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Respose object where resut will be saved. |

### ReturnValue

true if booklet was built successfully.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Makes booklet from the InputStream to outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input pdf stream. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | output pdf stream. |

### ReturnValue

True if operation was succeeded.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Makes customized booklet from the firstInputStream to outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | The input stream. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | output pdf stream. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | The left pages. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | The right pages. |

### ReturnValue

boolean - True for success, or false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) method


Makes booklet from the input stream and save result into output stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input PDF stream. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | output pdf stream. |
| pageSize | const System::SharedPtr\<PageSize\>\& | The page size of the output pdf file. |

### ReturnValue

True if operation was succeeded.


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Makes booklet from the firstInputStream to outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | The input stream. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | output pdf stream. |
| pageSize | const System::SharedPtr\<PageSize\>\& | The page size of the output pdf file. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | The left pages. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | The right pages. |

### ReturnValue

boolean - True for success, or false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Makes booklet from source file and stores result into HttpResponse objects.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Source file path. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Desired page size. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Aray of page numbers to be placed in left. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Array of page numbers to be placed in right. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be stored. |

### ReturnValue

True if operation was succeeded.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Makes booklet from source file and stores result into HttpResponse objects.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Source file path. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Desired page size in output file. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be stored. |

### ReturnValue

True if operation is succeeded.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&) method


Makes booklet from the input file to output file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Input pdf file path and name. |
| outputFile | const System::String\& | Output pdf file path and name. |

### ReturnValue

boolean - True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Makes customized booklet from the firstInputFile to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | The input file. |
| outputFile | const System::String\& | Output pdf file path and name. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | The left pages of the booklet. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | The right pages of the booklet. |

### ReturnValue

boolean - True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&) method


Makes booklet from the inputFile to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Input pdf file path and name. |
| outputFile | const System::String\& | Output pdf file path and name. |
| pageSize | const System::SharedPtr\<PageSize\>\& | The page size of the output pdf file. |

### ReturnValue

True if operation is succeeded.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Makes customized booklet from the firstInputFile to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | The input file. |
| outputFile | const System::String\& | Output pdf file path and name. |
| pageSize | const System::SharedPtr\<PageSize\>\& | The page size of the output pdf file. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | The left pages. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | The right pages. |

### ReturnValue

boolean - True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
