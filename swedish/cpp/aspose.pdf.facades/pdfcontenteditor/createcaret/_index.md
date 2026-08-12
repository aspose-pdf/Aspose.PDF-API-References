---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateCaret method"
linktitle: "CreateCaret"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateCaret method. Skapar caret-annotation i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor::CreateCaret method


Skapar marköranteckning.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateCaret(int32_t page, System::Drawing::Rectangle annotRect, System::Drawing::Rectangle caretRect, const System::String &symbol, const System::String &annotContents, System::Drawing::Color color)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | System::Drawing::Rectangle | Annotationsrektangeln som definierar placeringen av anmärkningen på sidan. |
| caretRect | System::Drawing::Rectangle | De faktiska gränserna för den underliggande caret. |
| symbol | const System::String\& | En symbol kommer att associeras med caret. Värdet kan vara: "P" (Paragraph), "None". |
| annotContents | const System::String\& | Innehållet i annotationen. |
| färg | System::Drawing::Color | Färgen på annotationen. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
