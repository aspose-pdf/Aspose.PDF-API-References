---
title: TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for Java API Reference
description: Determines action that will be done after replace of text fragment to more short.
type: docs
weight: 10
url: /java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextReplaceOptions.ReplaceAdjustment extends Enum<TextReplaceOptions.ReplaceAdjustment>
```

Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries adjust spaces between words to keep line length; WholeWordsHyphenation - tries distribute words between paragraph lines to keep paragraph's right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No action, replaced text may overlaps rest of the line |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Tries adjust spaces between words to keep line length |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Tries distribute words between paragraph lines to keep paragraph's right field |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Default) Shifts rest of the line according to changing length of text, length of the line may be changed |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) |  |
### None {#None}
```
public static final TextReplaceOptions.ReplaceAdjustment None
```


No action, replaced text may overlaps rest of the line

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final TextReplaceOptions.ReplaceAdjustment AdjustSpaceWidth
```


Tries adjust spaces between words to keep line length

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final TextReplaceOptions.ReplaceAdjustment WholeWordsHyphenation
```


Tries distribute words between paragraph lines to keep paragraph's right field

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final TextReplaceOptions.ReplaceAdjustment ShiftRestOfLine
```


(Default) Shifts rest of the line according to changing length of text, length of the line may be changed

### values() {#values--}
```
public static TextReplaceOptions.ReplaceAdjustment[] values()
```




**Returns:**
com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextReplaceOptions.ReplaceAdjustment valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ReplaceAdjustment](../../com.aspose.pdf/replaceadjustment)
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
