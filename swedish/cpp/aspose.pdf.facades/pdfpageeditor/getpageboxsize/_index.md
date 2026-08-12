---
title: "Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize metod"
linktitle: "GetPageBoxSize"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize metod. Returnerar storleken på den angivna rutan i dokumentet i C++."
type: docs
weight: 1300
url: /sv/cpp/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor::GetPageBoxSize method


Returnerar storleken på den angivna rutan i dokumentet.

```cpp
System::Drawing::Rectangle Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize(int32_t page, const System::String &pageBoxName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | int32_t | [Page](../../../aspose.pdf/page/) index. [Document](../../../aspose.pdf/document/) sidor är numrerade från 1. |
| pageBoxName | const System::String\& | Box-typnamn. Giltiga värden är: "art", "bleed", "crop", "media", "trim". |

### ReturnValue

[Rectangle](../../../aspose.pdf/rectangle/) which contains requested box.

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfPageEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
