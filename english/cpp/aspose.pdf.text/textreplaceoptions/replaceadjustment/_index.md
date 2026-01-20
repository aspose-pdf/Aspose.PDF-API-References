---
title: Aspose::Pdf::Text::TextReplaceOptions::ReplaceAdjustment enum
linktitle: ReplaceAdjustment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextReplaceOptions::ReplaceAdjustment enum. Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries adjust spaces between words to keep line length; WholeWordsHyphenation - tries distribute words between paragraph lines to keep paragraph''s right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.text/textreplaceoptions/replaceadjustment/
---
## ReplaceAdjustment enum


Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries adjust spaces between words to keep line length; WholeWordsHyphenation - tries distribute words between paragraph lines to keep paragraph's right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine.

```cpp
enum class ReplaceAdjustment
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No action, replaced text may overlaps rest of the line. |
| AdjustSpaceWidth | 1 | Tries adjust spaces between words to keep line length. |
| WholeWordsHyphenation | 2 | Tries distribute words between paragraph lines to keep paragraph's right field. |
| IsFormFillingMode | 4 | Tries to spread the words in the available white space using the paragraph width. If the text overflows, it will be hidden. |
| ShiftRestOfLine | 8 | (Default) Shifts rest of the line according to changing length of text, length of the line may be changed |

## See Also

* Class [TextReplaceOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
