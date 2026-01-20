---
title: Aspose::Pdf::Text::TextReplaceOptions::FontSizeAdjustment enum
linktitle: FontSizeAdjustment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextReplaceOptions::FontSizeAdjustment enum. Specifies a policy for how the font size of text should be adjusted to fit within a containing area in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf.text/textreplaceoptions/fontsizeadjustment/
---
## FontSizeAdjustment enum


Specifies a policy for how the font size of text should be adjusted to fit within a containing area.

```cpp
enum class FontSizeAdjustment
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | The font size is not changed. |
| ShrinkToFit | 1 | The font size is reduced if the text is too large to fit the bounds. The font size is never increased if the text is smaller than the bounds. |
| ScaleToFill | 2 | The font size is adjusted (both shrinking and growing) to make the text fill the bounds of the rectangle as much as possible. |

## See Also

* Class [TextReplaceOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
