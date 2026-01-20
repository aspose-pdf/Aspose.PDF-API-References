---
title: Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst method
linktitle: SplitFromFirst
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst method. Splits from start to specified location,and saves the front part in output Stream in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## PdfFileEditor::SplitFromFirst(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Splits from start to specified location,and saves the front part in output Stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(System::SharedPtr<System::IO::Stream> inputStream, int32_t location, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Source [Pdf](../../../aspose.pdf/) file Stream. |
| location | int32_t | The splitting point. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output file Stream. |

### ReturnValue

True for success, or false.
## Remarks



The streams are NOT closed after this operation.
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitFromFirst(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Splits document from start to specified location and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(System::SharedPtr<System::IO::Stream> inputStream, int32_t location, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of source document. |
| location | int32_t | The splitting point. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

True if operation was succeeded.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitFromFirst(System::String, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Splits document from first page to location and saves result into HttpResponse objects.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(System::String inputFile, int32_t location, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file name. |
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
## PdfFileEditor::SplitFromFirst(System::String, int32_t, System::String) method


Splits [Pdf](../../../aspose.pdf/) file from first page to specified location,and saves the front part as a new file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(System::String inputFile, int32_t location, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source [Pdf](../../../aspose.pdf/) file. |
| location | int32_t | The splitting point. |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) file. |

### ReturnValue

True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
