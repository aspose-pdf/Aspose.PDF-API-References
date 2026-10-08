---
title: "TextReplaceOptions.ReplaceAdjustment Enum"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
articleTitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextReplaceOptions.ReplaceAdjustment enum. Determines action that will be done after replace of text fragment to more short. None - no action..."
type: docs
weight: 640
url: "/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/"
product_version: "26.9"
---
## TextReplaceOptions.ReplaceAdjustment enumeration

Determines action that will be done after replace of text fragment to more short.
 None - no action, replaced text may overlaps rest of the line;
 AdjustSpaceWidth - tries adjust spaces between words to keep line length;
 WholeWordsHyphenation - tries distribute words between paragraph lines to keep paragraph's right field;
 ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed;
 Default value is ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No action, replaced text may overlaps rest of the line |
| AdjustSpaceWidth | `1` | Tries adjust spaces between words to keep line length |
| WholeWordsHyphenation | `2` | Tries distribute words between paragraph lines to keep paragraph's right field |
| IsFormFillingMode | `4` | Tries to spread the words in the available white space using the paragraph width. If the text overflows, it will be hidden. |
| ShiftRestOfLine | `8` | (Default) Shifts rest of the line according to changing length of text, length of the line may be changed |

### See Also

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

