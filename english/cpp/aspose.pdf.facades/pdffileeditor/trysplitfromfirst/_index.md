---
title: Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst method
linktitle: TrySplitFromFirst
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst method. Splits from start to specified location,and saves the front part in output Stream in C++.'
type: docs
weight: 7000
url: /cpp/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## PdfFileEditor::TrySplitFromFirst(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Splits from start to specified location,and saves the front part in output Stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(System::SharedPtr<System::IO::Stream> inputStream, int32_t location, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Source [Pdf](../../../aspose.pdf/) file Stream. |
| location | int32_t | The splitting point. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output file Stream. |

### ReturnValue

True for success, or false.
## Remarks



The streams are NOT closed after this operation. The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitFromFirst(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Splits document from start to specified location and stores result into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(System::SharedPtr<System::IO::Stream> inputStream, int32_t location, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of source document. |
| location | int32_t | The splitting point. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitFromFirst(System::String, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Splits document from first page to location and saves result into HttpResponse objects.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(System::String inputFile, int32_t location, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file name. |
| location | int32_t | Split point. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse objects. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitFromFirst(System::String, int32_t, System::String) method


Splits [Pdf](../../../aspose.pdf/) file from first page to specified location,and saves the front part as a new file.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(System::String inputFile, int32_t location, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source [Pdf](../../../aspose.pdf/) file. |
| location | int32_t | The splitting point. |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) file. |

### ReturnValue

True for success, or false.
## Remarks



The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
