---
title: Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents method
linktitle: TryResizeContents
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents method. Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object in C++.'
type: docs
weight: 6900
url: /cpp/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## PdfFileEditor::TryResizeContents(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::SharedPtr<System::IO::Stream> source, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream of source file. |
| pages | System::ArrayPtr\<int32_t\> | Array of pages to be resized. |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Resize parameters. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result is saved. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::SharedPtr<System::IO::Stream> source, System::SharedPtr<System::IO::Stream> destination, System::ArrayPtr<int32_t> pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream which contains source document. |
| destination | System::SharedPtr\<System::IO::Stream\> | Stream where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) method


Resizes contents of pages of the document.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::SharedPtr<System::IO::Stream> source, System::SharedPtr<System::IO::Stream> destination, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream with source document. |
| destination | System::SharedPtr\<System::IO::Stream\> | Stream with the destination document. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Resize parameters. |

### ReturnValue

Returns true if success.
## Remarks



The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::String source, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::String | Path to source file. |
| pages | System::ArrayPtr\<int32_t\> | Array of pages to be resized. |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Resize parameters. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result is saved. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks



The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::String, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::String source, System::String destination, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::String | Source document path. |
| destination | System::String | Destination document path. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes (page index starts from 1). |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Parameters of page resize. |

### ReturnValue

true if resize was successful.
## Remarks



The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
