---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink method"
linktitle: "CreateWebLink"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink metod. Skapar en webblänk i PDF‑dokument i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## PdfContentEditor::CreateWebLink(System::Drawing::Rectangle, const System::String\&, int32_t) method


Skapar en webb-länk i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink(System::Drawing::Rectangle rect, const System::String &url, int32_t originalPage)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| url | const System::String\& | Webblänkens destination. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till webblänken kommer att skapas. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateWebLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) method


Skapar en webb-länk i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink(System::Drawing::Rectangle rect, const System::String &url, int32_t originalPage, System::Drawing::Color clr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| url | const System::String\& | Webblänkens destination. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till webblänken kommer att skapas. |
| clr | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateWebLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Skapar en webb-länk i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink(System::Drawing::Rectangle rect, const System::String &url, int32_t originalPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| url | const System::String\& | Webblänkens destination. |
| originalPage | int32_t | Numret på den ursprungliga sidan på vilken rektangeln som är bunden till webblänken kommer att skapas. |
| clr | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Arrayen med åtgärder (medlemmar av PredefinedAction enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |

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
