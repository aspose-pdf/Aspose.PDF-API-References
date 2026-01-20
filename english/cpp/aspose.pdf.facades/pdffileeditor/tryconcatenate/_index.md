---
title: Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate method
linktitle: TryConcatenate
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate method. Concatenates documents in C++.'
type: docs
weight: 6300
url: /cpp/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## PdfFileEditor::TryConcatenate(System::ArrayPtr\<System::SharedPtr\<Document\>\>, System::SharedPtr\<Document\>) method


Concatenates documents.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::ArrayPtr<System::SharedPtr<Document>> src, System::SharedPtr<Document> dest)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | System::ArrayPtr\<System::SharedPtr\<Document\>\> | Array of source documents. |
| dest | System::SharedPtr\<Document\> | Destination document. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>) method


Concatenates files.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> inputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Array of streams to be concatenated. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Stream where result file will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Concatenates files and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> inputStream, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Streams array which contain files to concatenate. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object/ |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Concatenates files and saves reslt into HttpResposnse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::ArrayPtr<System::String> inputFiles, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | System::ArrayPtr\<System::String\> | Array of files to concatenate. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(System::ArrayPtr\<System::String\>, System::String) method


Concatenates files into one file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::ArrayPtr<System::String> inputFiles, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | System::ArrayPtr\<System::String\> | Array of files to concatenate. |
| outputFile | System::String | Name of output file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Merges two [Pdf](../../../aspose.pdf/) documents into a new [Pdf](../../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::SharedPtr<System::IO::Stream> firstInputStream, System::SharedPtr<System::IO::Stream> secInputStream, System::SharedPtr<System::IO::Stream> blankPageStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | System::SharedPtr\<System::IO::Stream\> | The first [Pdf](../../../aspose.pdf/) Stream. |
| secInputStream | System::SharedPtr\<System::IO::Stream\> | The second [Pdf](../../../aspose.pdf/) Stream. |
| blankPageStream | System::SharedPtr\<System::IO::Stream\> | The [Pdf](../../../aspose.pdf/) Stream with blank page. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output [Pdf](../../../aspose.pdf/) Stream. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(System::String, System::String, System::String, System::String) method


Merges two [Pdf](../../../aspose.pdf/) documents into a new [Pdf](../../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::String firstInputFile, System::String secInputFile, System::String blankPageFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | System::String | First file. |
| secInputFile | System::String | Second file. |
| blankPageFile | System::String | PDF file with blank page. |
| outputFile | System::String | Result file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(System::String, System::String, System::String) method


Concatenates two files.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(System::String firstInputFile, System::String secInputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | System::String | First file to concatenate. |
| secInputFile | System::String | Second file to concatenate. |
| outputFile | System::String | Output file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
