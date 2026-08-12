---
title: "Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle metod"
linktitle: "SetTextStyle"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle metod. Anger formateringen som bestäms av parametern textStyle för ett textfragment från index fromInd till index toInd i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## FreeTextAnnotation::SetTextStyle(int32_t, int32_t, RichTextFontStyles) method


Ställer in formateringen som bestäms av parametern textStyle för ett textfragment från index fromInd till index toInd.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(int32_t fromInd, int32_t toInd, RichTextFontStyles textStyles)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fromInd | int32_t | Startindex för textfragmentet (från 0). |
| toInd | int32_t | Slutindex för textfragmentet (räknat från 0, detta inkluderas inte). |
| textStyles | RichTextFontStyles | Stil(ar) som tillämpas på textfragmentet. |

## Se även

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## FreeTextAnnotation::SetTextStyle(RichTextFontStyles, const System::String\&, double, System::Drawing::Color) method


Ställer in formateringen som bestäms av parametern textStyle för all annotationstext.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(RichTextFontStyles textStyles, const System::String &fontName, double fontSize, System::Drawing::Color fontColor)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Stil(ar) som tillämpas på annoteringstexten. |
| fontName | const System::String\& | Typsnittsnamn som tillämpas på annoteringstexten. |
| fontSize | double | Typsnittsstorlek som tillämpas på annoteringstexten. |
| fontColor | System::Drawing::Color | Typsnittsfärg som tillämpas på annoteringstexten. |

## Se även

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
