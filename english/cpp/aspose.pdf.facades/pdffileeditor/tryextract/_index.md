---
title: Aspose::Pdf::Facades::PdfFileEditor::TryExtract method
linktitle: TryExtract
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryExtract method. Extracts pages specified by number array, saves as a new Pdf file in C++.'
type: docs
weight: 6500
url: /cpp/aspose.pdf.facades/pdffileeditor/tryextract/
---
## PdfFileEditor::TryExtract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Extracts pages specified by number array, saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input file Stream. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Index of page out of the input file. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Output file stream. |

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
## PdfFileEditor::TryExtract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Extracts specified pages form source file and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream of source document. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array of page numbers which will be extracted. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be stored. |

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
## PdfFileEditor::TryExtract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Extracts specified pages from source file and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Source file path. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array of page numbers which will be extracted. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be stored. |

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
## PdfFileEditor::TryExtract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Extracts pages specified by number array, saves as a new PDF file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Input file path. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Index of page out of the input file. |
| outputFile | const System::String\& | Output file path. |

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
## PdfFileEditor::TryExtract(const System::String\&, int32_t, int32_t, const System::String\&) method


Extracts pages from input file,saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Input [Pdf](../../../aspose.pdf/) file path. |
| startPage | int32_t | Start page number. |
| endPage | int32_t | End page number. |
| outputFile | const System::String\& | Output [Pdf](../../../aspose.pdf/) file path. |

### ReturnValue

True for success, or false.
## Remarks



The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
