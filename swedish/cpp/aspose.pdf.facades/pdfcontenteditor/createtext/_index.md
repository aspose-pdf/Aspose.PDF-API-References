---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateText method"
linktitle: "CreateText"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateText method. Skapar textanteckning i PDF-dokument i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor::CreateText method


Skapar textanteckning i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateText(System::Drawing::Rectangle rect, const System::String &title, const System::String &contents, bool open, const System::String &icon, int32_t page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Annotationsrektangeln som definierar placeringen av anmärkningen på sidan. |
| titel | const System::String\& | Titeln på anteckningen. |
| innehåll | const System::String\& | Innehållet i annotationen. |
| öppen | bool | En flagga som anger om anteckningen initialt ska visas öppen. |
| icon | const System::String\& | Namnet på en ikon kommer att användas vid visning av anteckningen. Detta värde kan vara: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| sida | int32_t | Numret på den ursprungliga sidan där textanteckningen kommer att skapas. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
