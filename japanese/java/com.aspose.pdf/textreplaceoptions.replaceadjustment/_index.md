---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストフラグメントを短く置換した後に実行されるアクションを決定します。None - アクションなし、置換されたテキストが行の残りと重なる可能性があります。AdjustSpaceWidth - 調整を試みます。"
type: docs
weight: 5270
url: /ja/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

テキストフラグメントを短く置換した後に実行されるアクションを決定します。None - アクションなし、置換されたテキストが行の残りと重なる可能性があります。AdjustSpaceWidth - 行長を保つために単語間のスペース幅を調整しようとします。WholeWordsHyphenation - 段落行間で単語を分配して段落の右端を保とうとします。ShiftRestOfLine - テキストの長さ変化に応じて行の残り部分をシフトし、行の長さが変わることがあります。デフォルト値は ShiftRestOfLine です。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | 行の長さを保つために単語間のスペースを調整しようとします。 |
| [IsFormFillingMode](#IsFormFillingMode) | 段落幅を使用して利用可能な空白領域に単語を広げようとします。テキストがはみ出す場合、非表示になります。 |
| [None](#None) | アクションなし、置換されたテキストが行の残りと重なる可能性があります。 |
| [ShiftRestOfLine](#ShiftRestOfLine) | (デフォルト) テキストの長さの変化に応じて行の残りをシフトし、行の長さが変わる可能性があります。 |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | 段落の右側余白を保つために、単語を段落行間に分配しようとします。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

行の長さを保つために単語間のスペースを調整しようとします。

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

段落幅を使用して利用可能な空白領域に単語を広げようとします。テキストがはみ出す場合、非表示になります。

### None {#None}
```
public static final int None
```

アクションなし、置換されたテキストが行の残りと重なる可能性があります。

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(デフォルト) テキストの長さの変化に応じて行の残りをシフトし、行の長さが変わる可能性があります。

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

段落の右側余白を保つために、単語を段落行間に分配しようとします。

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フラグ |  |  |
| flagToCheck |  |  |
