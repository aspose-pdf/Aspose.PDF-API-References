---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment 列挙型。テキストフラグメントを短く置き換えた後に行われるアクションを決定します。None - アクションなし、置き換えられたテキストは行の残りの部分と重なる可能性があります。AdjustSpaceWidth - 行の長さを維持するために単語間のスペースを調整しようとします。WholeWordsHyphenation - 段落の行間で単語を分配し、段落の右側を維持しようとします。ShiftRestOfLine - テキストの長さの変化に応じて行の残りをシフトします。行の長さは変更される可能性があります。デフォルト値は ShiftRestOfLine です。
type: docs
weight: 11020
url: /ja/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment 列挙型

テキストフラグメントを短く置き換えた後に行われるアクションを決定します。None - アクションなし、置き換えられたテキストは行の残りの部分と重なる可能性があります。AdjustSpaceWidth - 行の長さを維持するために単語間のスペースを調整しようとします。WholeWordsHyphenation - 段落の行間で単語を分配し、段落の右側を維持しようとします。ShiftRestOfLine - テキストの長さの変化に応じて行の残りをシフトします。行の長さは変更される可能性があります。デフォルト値は ShiftRestOfLine です。

```csharp
[Flags]
public enum ReplaceAdjustment
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | アクションなし、置き換えられたテキストは行の残りの部分と重なる可能性があります |
| AdjustSpaceWidth | `1` | 行の長さを維持するために単語間のスペースを調整しようとします |
| WholeWordsHyphenation | `2` | 段落の行間で単語を分配し、段落の右側を維持しようとします |
| IsFormFillingMode | `4` | 段落の幅を使用して利用可能な空白に単語を広げようとします。テキストがオーバーフローする場合は、隠されます。 |
| ShiftRestOfLine | `8` | (デフォルト) テキストの長さの変化に応じて行の残りをシフトします。行の長さは変更される可能性があります |

### 参照

* クラス [TextReplaceOptions](../textreplaceoptions/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)