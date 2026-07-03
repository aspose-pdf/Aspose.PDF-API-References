---
title: TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for Java API Reference
description: Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries to.
type: docs
weight: 5270
url: /java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries to adjust spaces between words to keep line length; WholeWordsHyphenation - tries to distribute words between paragraph lines to keep paragraph's right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine.

## Fields

| Field | Description |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Tries to adjust spaces between words to keep line length |
| [IsFormFillingMode](#IsFormFillingMode) | Tries to spread the words in the available white space using the paragraph width. If the text overflows, it will be hidden. |
| [None](#None) | No action, replaced text may overlaps rest of the line |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Default) Shifts rest of the line according to changing length of text, length of the line may be changed |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Tries to distribute words between paragraph lines to keep paragraph's right field |

## Methods

| Method | Description |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Tries to adjust spaces between words to keep line length

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Tries to spread the words in the available white space using the paragraph width. If the text overflows, it will be hidden.

### None {#None}
```
public static final int None
```

No action, replaced text may overlaps rest of the line

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Default) Shifts rest of the line according to changing length of text, length of the line may be changed

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Tries to distribute words between paragraph lines to keep paragraph's right field

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flag |  |  |
| flagToCheck |  |  |
