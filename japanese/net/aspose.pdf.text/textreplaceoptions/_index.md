---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptions クラス。テキスト置換オプションを表します
type: docs
weight: 11010
url: /ja/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions クラス

テキスト置換オプションを表します

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | 指定された置換後のアクションのために `TextReplaceOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | 指定されたスコープのために `TextReplaceOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | 置換調整が強制的に新しいテキスト行を作成する場合に使用される行間の値を取得または設定します。期待される値は置換されたテキストのフォントサイズの倍率です。デフォルトは 1.2 です。 |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | テキスト置換後にページ上のテキストを調整する際に、異なる段落を無視するかどうかを示す値を取得または設定します。 |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | TextReplaceOptions を使用する際に置換されたテキストの左位置調整を設定または取得します: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | より短いテキストフラグメントに置換された後に行われるアクションを取得または設定します。 |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | テキスト置換操作が適用されるスコープを取得または設定します |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | TextReplaceOptions を使用する際に置換されたテキストの右位置調整を設定または取得します: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### 参照

* クラス [TextOptions](../textoptions/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)