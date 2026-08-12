---
title: "Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle метод"
linktitle: "SetTextStyle"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle метод. Устанавливает форматирование, определяемое параметром textStyle, для фрагмента текста от индекса fromInd до индекса toInd в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## FreeTextAnnotation::SetTextStyle(int32_t, int32_t, RichTextFontStyles) method


Устанавливает форматирование, определяемое параметром textStyle, для фрагмента текста от индекса fromInd до индекса toInd.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(int32_t fromInd, int32_t toInd, RichTextFontStyles textStyles)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fromInd | int32_t | Начальный индекс фрагмента текста (от 0). |
| toInd | int32_t | Конечный индекс фрагмента текста (считается от 0, не включается). |
| textStyles | RichTextFontStyles | Применённые стили к фрагменту текста. |

## См. также

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## FreeTextAnnotation::SetTextStyle(RichTextFontStyles, const System::String\&, double, System::Drawing::Color) method


Устанавливает форматирование, определяемое параметром textStyle, для всего текста аннотации.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(RichTextFontStyles textStyles, const System::String &fontName, double fontSize, System::Drawing::Color fontColor)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Применённые стили к тексту аннотации. |
| fontName | const System::String\& | Применённое название шрифта к тексту аннотации. |
| fontSize | double | Применённый размер шрифта к тексту аннотации. |
| fontColor | System::Drawing::Color | Применённый цвет шрифта к тексту аннотации. |

## См. также

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
