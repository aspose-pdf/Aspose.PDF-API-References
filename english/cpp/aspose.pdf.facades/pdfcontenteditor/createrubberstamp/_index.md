---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp method
linktitle: CreateRubberStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp method. Creates a rubber stamp annotation in C++.'
type: docs
weight: 2200
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, System::String, System::Drawing::Color, System::SharedPtr\<System::IO::Stream\>) method


Creates a rubber stamp annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, System::String annotContents, System::Drawing::Color color, System::SharedPtr<System::IO::Stream> appearanceStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | System::String | The contents of the annotation. |
| color | System::Drawing::Color | The colour of the annotation. |
| appearanceStream | System::SharedPtr\<System::IO::Stream\> | The stream of appearance file. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, System::String, System::Drawing::Color, System::String) method


Creates a rubber stamp annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, System::String annotContents, System::Drawing::Color color, System::String appearanceFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | System::String | The contents of the annotation. |
| color | System::Drawing::Color | The colour of the annotation. |
| appearanceFile | System::String | The path of appearance file. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, System::String, System::String, System::Drawing::Color) method


Creates a rubber stamp annotation.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, System::String icon, System::String annotContents, System::Drawing::Color color)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| icon | System::String | An icon is to be used in displaying the annotation. Default value: 'Draft'. |
| annotContents | System::String | The contents of the annotation. |
| color | System::Drawing::Color | The color of the annotation. |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
