---
title: TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for Java API Reference
description: Determines action that will be done after replace of text fragment to more short.
type: docs
weight: 10
url: /java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class TextReplaceOptions.ReplaceAdjustment extends System.Enum
```

Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries adjust spaces between words to keep line length; WholeWordsHyphenation - tries distribute words between paragraph lines to keep paragraph's right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No action, replaced text may overlaps rest of the line |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Tries adjust spaces between words to keep line length |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Tries distribute words between paragraph lines to keep paragraph's right field |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Default) Shifts rest of the line according to changing length of text, length of the line may be changed |
### None {#None}
```
public static final int None
```


No action, replaced text may overlaps rest of the line

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```


Tries adjust spaces between words to keep line length

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```


Tries distribute words between paragraph lines to keep paragraph's right field

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```


(Default) Shifts rest of the line according to changing length of text, length of the line may be changed

