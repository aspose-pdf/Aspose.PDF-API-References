---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink metod"
linktitle: "CreateApplicationLink"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink metod. Skapar en länk för att starta ett program i PDF-dokument i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t) method


Skapar en länk för att starta ett program i PDF‑dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| application | const System::String\& | Sökvägen till programmet som ska startas. |
| sida | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) method


Skapar en länk för att starta ett program i PDF‑dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page, System::Drawing::Color clr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| application | const System::String\& | Sökvägen till programmet som ska startas. |
| sida | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| clr | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Skapar en länk för att starta ett program i PDF‑dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| application | const System::String\& | Sökvägen till programmet som ska startas. |
| sida | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| clr | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Arrayen med åtgärder (medlemmar av PredefinedAction enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |
## Anmärkningar



///
## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
