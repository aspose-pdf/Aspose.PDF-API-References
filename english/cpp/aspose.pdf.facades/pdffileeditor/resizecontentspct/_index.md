---
title: Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct method
linktitle: ResizeContentsPct
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct method. Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents in C++.'
type: docs
weight: 3600
url: /cpp/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## PdfFileEditor::ResizeContentsPct(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(System::SharedPtr<System::IO::Stream> source, System::SharedPtr<System::IO::Stream> destination, System::ArrayPtr<int32_t> pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream which contains source document. |
| destination | System::SharedPtr\<System::IO::Stream\> | Stream where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

### ReturnValue

true if resized sucessfully.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContentsPct(System::String, System::String, System::ArrayPtr\<int32_t\>, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(System::String source, System::String destination, System::ArrayPtr<int32_t> pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::String | Path to source document. |
| destination | System::String | Path where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

### ReturnValue

true if resize was successful.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
