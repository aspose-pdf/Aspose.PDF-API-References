---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink metod"
linktitle: "CreateLocalLink"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink metod. Skapar en lokal länk i PDF-dokumentet i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t) method


Skapar en lokal länk i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| desPage | int32_t | Destinationsidan. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln för den lokala länken skapas. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) method


Skapar en lokal länk i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| desPage | int32_t | Destinationsidan. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln för den lokala länken skapas. |
| clr | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Skapar en lokal länk i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| desPage | int32_t | Destinationsidan. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln för den lokala länken skapas. |
| clr | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Arrayen med åtgärder (medlemmar av PredefinedAction enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
