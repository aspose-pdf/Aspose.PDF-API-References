---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink method
linktitle: CreateApplicationLink
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink method. Creates a link to launch an application in PDF document in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, System::String, int32_t) method


Creates a link to launch an application in PDF document.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, System::String application, int32_t page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| application | System::String | The path of application to be launched. |
| page | int32_t | The number of original page where rectangle bound with link will be created. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, System::String, int32_t, System::Drawing::Color) method


Creates a link to launch an application in PDF document.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, System::String application, int32_t page, System::Drawing::Color clr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| application | System::String | The path of application to be launched. |
| page | int32_t | The number of original page where rectangle bound with link will be created. |
| clr | System::Drawing::Color | The colour of rectangle for active click. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, System::String, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) method


Creates a link to launch an application in PDF document.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, System::String application, int32_t page, System::Drawing::Color clr, System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> actionName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| application | System::String | The path of application to be launched. |
| page | int32_t | The number of original page where rectangle bound with link will be created. |
| clr | System::Drawing::Color | The colour of rectangle for active click. |
| actionName | System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\> | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |
## Remarks



/// 
## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
