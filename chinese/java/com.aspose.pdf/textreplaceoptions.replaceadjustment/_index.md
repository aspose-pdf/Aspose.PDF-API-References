---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF for Java API 参考"
description: "确定在将文本片段替换为更短后将执行的操作。None - 不执行任何操作，替换后的文本可能会覆盖行的其余部分；AdjustSpaceWidth - 尝试。"
type: docs
weight: 5270
url: /zh/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

确定在将文本片段替换为更短后将执行的操作。None - 不执行任何操作，替换后的文本可能会覆盖行的其余部分；AdjustSpaceWidth - 尝试调整单词之间的空格以保持行长度；WholeWordsHyphenation - 尝试在段落行之间分配单词以保持段落的右侧对齐；ShiftRestOfLine - 根据文本长度的变化移动行的其余部分，行的长度可能会被改变；默认值为 ShiftRestOfLine。

## 字段

| 字段 | 描述 |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | 尝试调整单词之间的空格以保持行长度。 |
| [IsFormFillingMode](#IsFormFillingMode) | 尝试使用段落宽度在可用的空白区域中展开单词。如果文本溢出，将被隐藏。 |
| [None](#None) | 不执行任何操作，替换后的文本可能会覆盖行的其余部分。 |
| [ShiftRestOfLine](#ShiftRestOfLine) | (默认) 根据文本长度的变化移动行的其余部分，行的长度可能会改变。 |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | 尝试在段落行之间分配单词，以保持段落的右侧对齐。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

尝试调整单词之间的空格以保持行长度。

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

尝试使用段落宽度在可用的空白区域中展开单词。如果文本溢出，将被隐藏。

### None {#None}
```
public static final int None
```

不执行任何操作，替换后的文本可能会覆盖行的其余部分。

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(默认) 根据文本长度的变化移动行的其余部分，行的长度可能会改变。

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

尝试在段落行之间分配单词，以保持段落的右侧对齐。

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flag |  |  |
| flagToCheck |  |  |
