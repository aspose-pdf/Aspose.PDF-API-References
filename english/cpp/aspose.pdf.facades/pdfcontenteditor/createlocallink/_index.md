---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink method
linktitle: CreateLocalLink
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink method. Creates a local link in PDF document in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t) method


Creates a local link in PDF document.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| desPage | int32_t | The destination page. |
| originalPage | int32_t | The number of original page where rectangle bound with local link will be created. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) method


Creates a local link in PDF document.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| desPage | int32_t | The destination page. |
| originalPage | int32_t | The number of original page where rectangle bound with local link will be created. |
| clr | System::Drawing::Color | The colour of rectangle for active click. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) method


Creates a local link in PDF document.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr, System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> actionName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| desPage | int32_t | The destination page. |
| originalPage | int32_t | The number of original page where rectangle bound with local link will be created. |
| clr | System::Drawing::Color | The colour of rectangle for active click. |
| actionName | System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\> | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
