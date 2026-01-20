---
title: Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd method
linktitle: SplitToEnd
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd method. Splits from specified location, and saves the rear part as a new file Stream in C++.'
type: docs
weight: 6000
url: /cpp/aspose.pdf.facades/pdffileeditor/splittoend/
---
## PdfFileEditor::SplitToEnd(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Splits from specified location, and saves the rear part as a new file Stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(System::SharedPtr<System::IO::Stream> inputStream, int32_t location, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Source [Pdf](../../../aspose.pdf/) file Stream. |
| location | int32_t | The splitting position. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output [Pdf](../../../aspose.pdf/) file Stream. |

### ReturnValue

True for success, or false.
## Remarks



The streams are NOT closed after this operation unless CloseConcatedStreams is specified.
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Splits from specified location, and saves the rear part into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(System::SharedPtr<System::IO::Stream> inputStream, int32_t location, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Source document stream. |
| location | int32_t | Split point. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object. |

### ReturnValue

true if splitting was successful.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(System::String, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Splits from specified location, and saves the rear part into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(System::String inputFile, int32_t location, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | source file name. |
| location | int32_t | Split point. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse objects. |

### ReturnValue

True if operation was succeeded.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(System::String, int32_t, System::String) method


Splits from location, and saves the rear part as a new file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(System::String inputFile, int32_t location, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source [Pdf](../../../aspose.pdf/) file. |
| location | int32_t | The splitting position. |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) file path. |

### ReturnValue

True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
