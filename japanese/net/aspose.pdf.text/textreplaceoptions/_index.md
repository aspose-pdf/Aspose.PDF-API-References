---
title: "クラス TextReplaceOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextReplaceOptions クラス。テキスト置換オプションを表します"
type: docs
weight: 11190
url: /ja/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

テキスト置換オプションを表します。

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | 指定された置換後アクション用に `TextReplaceOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | 指定されたスコープ用に `TextReplaceOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | 置換調整が強制的に新しいテキスト行を作成する場合に使用される行間の値を取得または設定します。期待される値は置換されたテキストのフォントサイズの倍率です。デフォルトは 1.2 です。 |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | [`Rectangle`](./rectangle/) で定義された境界内に収まるようフォントサイズを調整するポリシーを取得または設定します。 |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | テキスト置換後にページ上のテキストを調整する際、個別の段落を無視するかどうかを示す値を取得または設定します。 |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | TextReplaceOptions を使用する際の置換テキストの左位置調整を設定または取得します: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | 置換後のテキストに合わせる矩形を取得または設定します。 |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | テキストフラグメントの置換後に実行されるアクションを取得または設定します（より短くするため）。 |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | テキスト置換操作が適用されるスコープを取得または設定します。 |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | TextReplaceOptions を使用する際の置換テキストの右位置調整を設定または取得します: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### 関連項目

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


