---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink metod"
linktitle: "CreatePdfDocumentLink"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink metod. Skapar en länk till en annan PDF-dokumentsida i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t) method


Skapar en länk till en annan PDF-dokumentsida.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| remotePdf | const System::String\& | PDF-dokumentet vars sida ska öppnas. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| destinationPage | int32_t | Destinationsidan. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) method


Skapar en länk till en annan PDF-dokumentsida.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| remotePdf | const System::String\& | PDF-dokumentet vars sida ska öppnas. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| destinationPage | int32_t | Destinationsidan. |
| clr | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Skapar en länk till en annan PDF-dokumentsida.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| remotePdf | const System::String\& | PDF-dokumentet vars sida ska öppnas. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| destinationPage | int32_t | Destinationsidan. |
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
