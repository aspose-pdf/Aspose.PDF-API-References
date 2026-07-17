---
title: Aspose::Pdf::Facades::PdfFileEditor::AddMargins method
linktitle: AddMargins
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::AddMargins method. Resizes page contents and add specifed margins. Margins are specified in default space units in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.facades/pdffileeditor/addmargins/
---
## PdfFileEditor::AddMargins(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Resizes page contents and add specifed margins. Margins are specified in default space units.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Stream which contains source document. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Stream where resultant document will be saved. |
| pages | const System::ArrayPtr\<int32_t\>\& | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margin. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

### ReturnValue

true if operation was successful.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddMargins(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Resizes page contents and add specifed margins. Margins are specified in default space units.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | const System::String\& | Path to source document. |
| destination | const System::String\& | Path where resultant document will be saved. |
| pages | const System::ArrayPtr\<int32_t\>\& | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margin. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

### ReturnValue

true if resize was successful.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
