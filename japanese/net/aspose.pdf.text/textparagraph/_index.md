---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextParagraph クラス。複数行のテキストオブジェクトとしてテキスト段落を表します
type: docs
weight: 10990
url: /ja/net/aspose.pdf.text/textparagraph/
---
## TextParagraph クラス

複数行のテキストオブジェクトとしてテキスト段落を表します。

```csharp
public sealed class TextParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextParagraph](textparagraph/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | 次の行のインデント値を取得または設定します。非ゼロの値に設定すると、FormattingOptions.SubsequentLinesIndent 値に対して優位性があります。 |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | 書式設定オプションを取得または設定します。 |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | 段落内のテキストの水平揃えを取得または設定します。[`Rectangle`](./rectangle/)。 |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | テキストが均等揃えかどうかの値を取得または設定します。 |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | パディングを取得または設定します。 |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | 段落の位置を取得または設定します。 |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | 段落の矩形を取得または設定します。 |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | 回転角度を度単位で取得または設定します。 |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | 次の行のインデント値を取得または設定します。非ゼロの値に設定すると、FormattingOptions.SubsequentLinesIndent 値に対して優位性があります。 |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | 段落に配置されたテキストの矩形を取得します。 |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | 段落内のテキストの垂直揃えを取得または設定します。[`Rectangle`](./rectangle/)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | テキスト行を追加します |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | テキスト状態パラメータを持つテキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | テキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | テキスト状態パラメータを持つテキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | テキスト状態パラメータを持つテキスト行を追加します。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | テキスト状態パラメータを持つテキスト行を追加します |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | テキスト状態パラメータを持つテキスト行を追加します |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | TextParagraph の編集を開始します。 |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | TextParagraph の編集を終了します。 |

## 例

この例は、テキスト段落オブジェクトを作成し、それを Pdf ページに追加する方法を示しています。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)