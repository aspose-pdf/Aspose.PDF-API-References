---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink method
linktitle: CreateCustomActionLink
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink method. Creates a link to custom actions in PDF document in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor::CreateCustomActionLink method


Creates a link to custom actions in PDF document.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink(System::Drawing::Rectangle rect, int32_t originalPage, System::Drawing::Color color, System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> actionName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| originalPage | int32_t | The number of original page where rectangle bound with link will be created. |
| color | System::Drawing::Color | The colour of rectangle for active click. |
| actionName | System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\> | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |
## Remarks



/// 
## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
