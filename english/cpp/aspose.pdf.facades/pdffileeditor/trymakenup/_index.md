---
title: Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp method
linktitle: TryMakeNUp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp method. Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false in C++.'
type: docs
weight: 6800
url: /cpp/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## PdfFileEditor::TryMakeNUp(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>, bool) method


Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> inputStreams, System::SharedPtr<System::IO::Stream> outputStream, bool isSidewise)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Input [Pdf](../../../aspose.pdf/) streams. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |
| isSidewise | bool | Piled up way, true for horizontally and false for vertically. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::ArrayPtr\<System::String\>, System::String, bool) method


Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::ArrayPtr<System::String> inputFiles, System::String outputFile, bool isSidewise)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | System::ArrayPtr\<System::String\> | Input [Pdf](../../../aspose.pdf/) files. |
| outputFile | System::String | Output pdf file path and name. |
| isSidewise | bool | Piled up way, true for horizontally and false for vertically. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Makes N-Up document from the two input PDF streams to outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> firstInputStream, System::SharedPtr<System::IO::Stream> secondInputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | System::SharedPtr\<System::IO::Stream\> | first input stream. |
| secondInputStream | System::SharedPtr\<System::IO::Stream\> | second input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |

### ReturnValue

true if operation was completed successfully; otherwise, false
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of source document. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | [Page](../../../aspose.pdf/page/) size in result file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, int32_t x, int32_t y, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of input document. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t) method


Makes N-Up document from the input stream and saves result into output stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, int32_t x, int32_t y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input pdf stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>) method


Makes N-Up document from the first input stream to output stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input pdf stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, System::String, System::String) method


Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String firstInputFile, System::String secondInputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | System::String | first input file. |
| secondInputFile | System::String | second input file. |
| outputFile | System::String | Output pdf file path and name. |

### ReturnValue

true if operation was completed successfully; otherwise, false
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Path to source file. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | [Page](../../../aspose.pdf/page/) size in result file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, int32_t x, int32_t y, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file name. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, System::String, int32_t, int32_t) method


Makes N-Up document from the firstInputFile to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, System::String outputFile, int32_t x, int32_t y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |

### ReturnValue

true if operation was completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>) method


Makes N-Up document from the input file to outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, System::String outputFile, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
