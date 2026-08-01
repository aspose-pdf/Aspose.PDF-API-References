---
title: "クラス TextParagraph"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextParagraph クラス。テキスト段落を複数行テキストオブジェクトとして表します"
type: docs
weight: 11170
url: /ja/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

テキスト段落を複数行テキストオブジェクトとして表します。

```csharp
public sealed class TextParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextParagraph](textparagraph/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | 後続行のインデント値を取得または設定します。0 以外の値に設定すると、FormattingOptions.SubsequentLinesIndent の値より優位になります。 |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | 書式設定オプションを取得または設定します。 |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | 段落内のテキストの水平配置を取得または設定します（[`Rectangle`](./rectangle/)）。 |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | テキストが両端揃えかどうかの値を取得または設定します。 |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | 余白を取得または設定します。 |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | 段落の位置を取得または設定します。 |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | 段落の rectangle を取得または設定します。 |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | 回転角度（度）を取得または設定します。 |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | 後続行のインデント値を取得または設定します。0 以外の値に設定すると、FormattingOptions.SubsequentLinesIndent の値より優位になります。 |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | 段落に配置されたテキストの矩形を取得します。 |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | 段落の[`Rectangle`](./rectangle/)内のテキストの垂直位置揃えを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | テキスト行を追加します |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | テキスト状態パラメータを使用してテキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | テキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | テキスト状態パラメータを使用してテキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | テキスト状態パラメータを使用してテキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | テキスト状態パラメータを使用してテキスト行を追加します |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | テキスト状態パラメータを使用してテキスト行を追加します |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | TextParagraph の編集を開始します。 |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | TextParagraph の編集を終了します。 |

## 例

この例では、テキスト段落オブジェクトの作成方法とそれを Pdf ページに追加する方法を示しています。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// テキスト段落を作成する
TextParagraph paragraph = new TextParagraph();
           
// 段落の矩形を設定する
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// ワードラップオプションを設定する
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// 文字列行を追加する
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// TextBuilder を使用して段落を Pdf ページに追加する
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// Pdf ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


