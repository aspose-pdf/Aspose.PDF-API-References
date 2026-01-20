---
title: Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle method
linktitle: SetTextStyle
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle method. Sets the formatting determined by the parameter textStyle for a text fragment from fromInd index to toInd index in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## FreeTextAnnotation::SetTextStyle(int32_t, int32_t, RichTextFontStyles) method


Sets the formatting determined by the parameter textStyle for a text fragment from fromInd index to toInd index.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(int32_t fromInd, int32_t toInd, RichTextFontStyles textStyles)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fromInd | int32_t | Starting index of the text fragment (from 0). |
| toInd | int32_t | End index of the text fragment (counting from 0, this not included). |
| textStyles | RichTextFontStyles | Style(s) applied for text fragment. |

## See Also

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## FreeTextAnnotation::SetTextStyle(RichTextFontStyles, System::String, double, System::Drawing::Color) method


Sets the formatting determined by the parameter textStyle for all annotation text.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(RichTextFontStyles textStyles, System::String fontName, double fontSize, System::Drawing::Color fontColor)
```


| Parameter | Type | Description |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Style(s) applied for annotation text. |
| fontName | System::String | Font name applied for annotation text. |
| fontSize | double | Font size applied for annotation text. |
| fontColor | System::Drawing::Color | Font color applied for annotation text. |

## See Also

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
