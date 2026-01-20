---
title: Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize method
linktitle: GetPageBoxSize
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize method. Returns size of specified box in document in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor::GetPageBoxSize method


Returns size of specified box in document.

```cpp
System::Drawing::Rectangle Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize(int32_t page, System::String pageBoxName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | [Page](../../../aspose.pdf/page/) index. [Document](../../../aspose.pdf/document/) pages are numbered from 1. |
| pageBoxName | System::String | Box type name. Valid values are: "art", "bleed", "crop", "media", "trim". |

### ReturnValue

[Rectangle](../../../aspose.pdf/rectangle/) which contains requested box.

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfPageEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
