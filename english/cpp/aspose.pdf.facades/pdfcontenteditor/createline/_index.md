---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateLine method
linktitle: CreateLine
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateLine method. Creates line annotation in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor::CreateLine method


Creates line annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLine(System::Drawing::Rectangle rect, System::String contents, float x1, float y1, float x2, float y2, int32_t page, int32_t border, System::Drawing::Color clr, System::String borderStyle, System::ArrayPtr<int32_t> dashArray, System::ArrayPtr<System::String> LEArray)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | System::String | The contents of the annotation. |
| x1 | float | The starting horizontal coordinate of the line. |
| y1 | float | The starting vertical coordinate of the line. |
| x2 | float | The ending horizontal coordinate of the line. |
| y2 | float | The ending vertical coordinate of the line. |
| page | int32_t | The number of original page where the annotation will be created. |
| border | int32_t | The border width in points. If this value is 0 no border is drawn. Default value is 1. |
| clr | System::Drawing::Color | The color of line. |
| borderStyle | System::String | The border style specifying the width and dash pattern to be used in drawing the line. This value can be: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | System::ArrayPtr\<int32_t\> | A dash array defining a pattern of dashes and gaps to be used in drawing a dashed border. If it is used, borderSyle must be accordingly set to "D". |
| LEArray | System::ArrayPtr\<System::String\> | An array of two values respectively specifying the beginning and ending style of the drawing line. The values can be: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
