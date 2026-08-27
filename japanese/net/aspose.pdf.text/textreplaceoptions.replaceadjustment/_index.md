---
title: "列挙体 TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment 列挙体。テキストフラグメントを短く置換した後に実行されるアクションを決定します。None はアクションなしで、置換されたテキストが行の残りと重なる可能性があります。AdjustSpaceWidth は行の長さを保つために単語間のスペースを調整しようとします。WholeWordsHyphenation は段落行間で単語を分配し、段落の右端を揃えようとします。ShiftRestOfLine はテキストの長さの変化に応じて行の残りをシフトし、行の長さが変わる可能性があります。デフォルト値は ShiftRestOfLine です。"
type: docs
weight: 11210
url: /ja/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

テキストフラグメントを短く置換した後に実行されるアクションを決定します。None - アクションなし、置換されたテキストが行の残りと重なる可能性があります；AdjustSpaceWidth - 行の長さを保つために単語間のスペースを調整しようとします；WholeWordsHyphenation - 段落行間で単語を分配し、段落の右端を揃えようとします；ShiftRestOfLine - テキストの長さの変化に応じて行の残りをシフトし、行の長さが変わる可能性があります；デフォルト値は ShiftRestOfLine です。

```csharp
[Flags]
public enum ReplaceAdjustment
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | アクションなし、置換されたテキストが行の残りと重なる可能性があります |
| AdjustSpaceWidth | `1` | 行の長さを保つために単語間のスペースを調整しようとします |
| WholeWordsHyphenation | `2` | 段落行間で単語を分配し、段落の右端を揃えようとします |
| IsFormFillingMode | `4` | 段落幅を利用して利用可能な空白領域に単語を広げようとします。テキストがはみ出す場合、非表示になります。 |
| ShiftRestOfLine | `8` | （デフォルト）テキストの長さの変化に応じて行の残りをシフトし、行の長さが変わる可能性があります |

### 関連項目

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


