---
title: Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct method
linktitle: AddMarginsPct
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct method. Resizes page contents and add specified margins. Margins are specified in percents of intitial page size in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## PdfFileEditor::AddMarginsPct(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double, double, double) method


Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct(System::SharedPtr<System::IO::Stream> source, System::SharedPtr<System::IO::Stream> destination, System::ArrayPtr<int32_t> pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream which contains source document. |
| destination | System::SharedPtr\<System::IO::Stream\> | Stream where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margin in percents of initial page size. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

### ReturnValue

true if action was performed successfully.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddMarginsPct(System::String, System::String, System::ArrayPtr\<int32_t\>, double, double, double, double) method


Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct(System::String source, System::String destination, System::ArrayPtr<int32_t> pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::String | Path to source document. |
| destination | System::String | Path where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margin in percents of initial page size. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

### ReturnValue

true if resize was successful

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
