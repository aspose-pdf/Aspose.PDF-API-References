---
title: Aspose::Pdf::Facades::PdfFileEditor::ResizeContents method
linktitle: ResizeContents
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::ResizeContents method. Resizes pages of document. Blank margins are added around of shrinked page in C++.'
type: docs
weight: 3500
url: /cpp/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## PdfFileEditor::ResizeContents(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Resizes pages of document. Blank margins are added around of shrinked page.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<Document> &source, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::SharedPtr\<Document\>\& | Source document. |
| parameters | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Resize parameters. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<Document\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Resizes pages of document. Blank margins are added around of shrinked page.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<Document> &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::SharedPtr\<Document\>\& | Source document. |
| pages | System::ArrayPtr\<int32_t\> | List of page indexes. |
| parameters | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Resize parameters. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Stream which contains source document. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Stream where resultant document will be saved. |
| pages | const System::ArrayPtr\<int32_t\>\& | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

### ReturnValue

True if resize was successful.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Resizes contents of pages of the document.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Stream with source document. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Stream with the destination document. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. |
| parameters | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Resize parameters. |

### ReturnValue

Returns true if success.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Stream of source file. |
| pages | System::ArrayPtr\<int32_t\> | Array of pages to be resized. |
| parameters | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Resize parameters. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result is saved. |

### ReturnValue

True if operation was succeeded.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::String\& | Path to source document. |
| destination | const System::String\& | Path where resultant document will be saved. |
| pages | const System::ArrayPtr\<int32_t\>\& | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

### ReturnValue

true if resize was successful.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, const System::String\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, const System::String &destination, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::String\& | Source document path. |
| destination | const System::String\& | Destination document path. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes (page index starts from 1). |
| parameters | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parameters of page resize. |

### ReturnValue

true if resize was successful.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::String\& | Path to source file. |
| pages | System::ArrayPtr\<int32_t\> | Array of pages to be resized. |
| parameters | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Resize parameters. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result is saved. |

### ReturnValue

True if operation was succeeded.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
