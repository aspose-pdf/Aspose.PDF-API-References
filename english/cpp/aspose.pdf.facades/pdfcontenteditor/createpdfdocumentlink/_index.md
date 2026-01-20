---
title: Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink method
linktitle: CreatePdfDocumentLink
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink method. Creates a link to another PDF document page in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, System::String, int32_t, int32_t) method


Creates a link to another PDF document page.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, System::String remotePdf, int32_t originalPage, int32_t destinationPage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| remotePdf | System::String | The PDF document which page will be opened. |
| originalPage | int32_t | The number of original page where rectangle bound with link will be created. |
| destinationPage | int32_t | The destination page. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, System::String, int32_t, int32_t, System::Drawing::Color) method


Creates a link to another PDF document page.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, System::String remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| remotePdf | System::String | The PDF document which page will be opened. |
| originalPage | int32_t | The number of original page where rectangle bound with link will be created. |
| destinationPage | int32_t | The destination page. |
| clr | System::Drawing::Color | The colour of rectangle for active click. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, System::String, int32_t, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) method


Creates a link to another PDF document page.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, System::String remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr, System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> actionName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| remotePdf | System::String | The PDF document which page will be opened. |
| originalPage | int32_t | The number of original page where rectangle bound with link will be created. |
| destinationPage | int32_t | The destination page. |
| clr | System::Drawing::Color | The colour of rectangle for active click. |
| actionName | System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\> | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

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
