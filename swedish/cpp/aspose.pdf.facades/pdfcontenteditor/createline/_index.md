---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateLine metod"
linktitle: "CreateLine"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateLine metod. Skapar linjeanteckning i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor::CreateLine method


Skapar linjeanteckning.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLine(System::Drawing::Rectangle rect, const System::String &contents, float x1, float y1, float x2, float y2, int32_t page, int32_t border, System::Drawing::Color clr, const System::String &borderStyle, const System::ArrayPtr<int32_t> &dashArray, const System::ArrayPtr<System::String> &LEArray)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Annotationsrektangeln som definierar placeringen av anmärkningen på sidan. |
| innehåll | const System::String\& | Innehållet i annotationen. |
| x1 | float | Den startande horisontella koordinaten för linjen. |
| y1 | float | Den startande vertikala koordinaten för linjen. |
| x2 | float | Den avslutande horisontella koordinaten för linjen. |
| y2 | float | Den avslutande vertikala koordinaten för linjen. |
| sida | int32_t | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| kant | int32_t | Kantens bredd i punkter. Om detta värde är 0 ritas ingen kant. Standardvärdet är 1. |
| clr | System::Drawing::Color | Färgen på linjen. |
| borderStyle | const System::String\& | Kantstilen som specificerar bredden och streckmönstret som ska användas vid ritning av linjen. Detta värde kan vara: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | const System::ArrayPtr\<int32_t\>\& | Ett streckarray som definierar ett mönster av streck och mellanrum som ska användas vid ritning av en streckad kant. Om det används måste borderSyle sättas till "D". |
| LEArray | const System::ArrayPtr\<System::String\>\& | En array med två värden som respektive specificerar början och slutstil för den ritade linjen. Värdena kan vara: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
