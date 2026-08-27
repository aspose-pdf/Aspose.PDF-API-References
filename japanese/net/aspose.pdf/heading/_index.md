---
title: "クラス Heading"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Heading クラス。見出しを表します。"
type: docs
weight: 5590
url: /ja/net/aspose.pdf/heading/
---
## Heading class

見出しを表します。

```csharp
public sealed class Heading : TextFragment
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Heading](heading/)(int) | Cell クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトで表されるテキストの位置を取得します。Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。 |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | 対象ページを取得します。 |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 段落の末尾ノートを取得または設定します。（PDF 生成時のみ） |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 段落のフットノートを取得または設定します。（PDF 生成時のみ） |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment を含むフォームオブジェクトを取得します |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | テキストフラグメントの水平揃えを取得または設定します。 |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | フラグメントのハイパーリンクを設定します |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | 見出しが自動的に番号付けされるかどうかを取得します。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | 見出しが目次リストに含まれるかどうかを取得します。 |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | レベルを取得します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment を含むページを取得します |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトで表されるテキストの位置を取得または設定します。 |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment の矩形を取得します |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | テキスト置換オプションを取得します。オプションはフラグメントテキストが短くまたは長く置換される際の動作を定義します。 |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 現在の [`TextFragment`](../../aspose.pdf.text/textfragment/) のテキストセグメントを取得します。 |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | 見出しの開始番号を取得します。 |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | スタイルを取得または設定します。 |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトが表す文字列テキストオブジェクトを取得または設定します。 |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。 |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトが表すテキストのテキスト状態を取得または設定します。 |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | この見出しを含むページを取得します。 |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | この見出しの上部 Y 座標を取得します。 |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | ユーザーラベルを取得または設定します。 |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | テキストフラグメントの垂直揃えを取得または設定します。 |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | この段落の折り返し行数を取得または設定します。（PDF 生成時のみ） |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | 見出しを複製します。 |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | すべてのセグメントを含む見出しを複製します。 |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | 指定された [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) を取得し、[`TextFragment`](../../aspose.pdf.text/textfragment/) テキストの一部を表します。 |

### 関連項目

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


