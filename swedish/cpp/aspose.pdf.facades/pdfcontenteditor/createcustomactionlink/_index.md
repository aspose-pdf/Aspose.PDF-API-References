---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink metod"
linktitle: "CreateCustomActionLink"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink metod. Skapar en länk till anpassade åtgärder i PDF-dokument i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor::CreateCustomActionLink method


Skapar en länk till anpassade åtgärder i PDF-dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink(System::Drawing::Rectangle rect, int32_t originalPage, System::Drawing::Color color, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Rektangeln för aktivt klick. |
| originalPage | int32_t | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| färg | System::Drawing::Color | Färgen på rektangeln för aktivt klick. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Arrayen med åtgärder (medlemmar av PredefinedAction enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |
## Anmärkningar



///
## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
