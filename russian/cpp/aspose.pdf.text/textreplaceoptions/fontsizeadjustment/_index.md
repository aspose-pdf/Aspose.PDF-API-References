---
title: "Aspose::Pdf::Text::TextReplaceOptions::FontSizeAdjustment enum"
linktitle: "FontSizeAdjustment"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextReplaceOptions::FontSizeAdjustment enum. Задает политику того, как размер шрифта текста должен корректироваться, чтобы вписаться в содержащую область в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.text/textreplaceoptions/fontsizeadjustment/
---
## FontSizeAdjustment enum


Указывает политику того, как размер шрифта текста должен корректироваться, чтобы вписаться в ограничивающую область.

```cpp
enum class FontSizeAdjustment
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Размер шрифта не изменяется. |
| ShrinkToFit | 1 | Размер шрифта уменьшается, если текст слишком велик, чтобы поместиться в границы. Размер шрифта никогда не увеличивается, если текст меньше границ. |
| ScaleToFill | 2 | Размер шрифта корректируется (как уменьшение, так и увеличение), чтобы текст заполнял границы прямоугольника насколько это возможно. |

## См. также

* Class [TextReplaceOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
