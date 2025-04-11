---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Heading クラス。見出しを表します
type: docs
weight: 5470
url: /ja/net/aspose.pdf/heading/
---
## 見出しクラス

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
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトで表されるテキストの位置を取得します。Position 構造体の YIndent はテキストフラグメントの基準線座標を表します。 |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | 目的のページを取得します。 |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 段落のエンドノートを取得または設定します。（PDF生成専用） |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 段落のフットノートを取得または設定します。（PDF生成専用） |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment を含むフォームオブジェクトを取得します。 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | テキストフラグメントの水平配置を取得または設定します。 |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | フラグメントのハイパーリンクを設定します。 |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | 見出しが自動的に番号付けされるべきかどうかを取得します。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | 見出しが目次リストに含まれるべきかどうかを取得します。 |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | レベルを取得します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側の余白を取得または設定します。（PDF生成用） |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment を含むページを取得します。 |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトで表されるテキストの位置を取得または設定します。 |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment の矩形を取得します。 |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | テキスト置換オプションを取得します。オプションは、フラグメントテキストが短く/長く置き換えられるときの動作を定義します。 |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 現在の [`TextFragment`](../../aspose.pdf.text/textfragment/) のテキストセグメントを取得します。 |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | 見出しの開始番号を取得します。 |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | スタイルを取得または設定します。 |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトが表す文字列テキストオブジェクトを取得または設定します。 |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは、要求された記号がフォントで書き込めない場合の特別な動作を定義します。 |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) オブジェクトが表すテキストのテキスト状態を取得または設定します。 |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | この見出しを含むページを取得します。 |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | この見出しの上部 Y を取得します。 |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | ユーザーラベルを取得または設定します。 |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | テキストフラグメントの垂直配置を取得または設定します。 |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | この段落の折り返し行数を取得または設定します。（PDF生成専用） |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z-オーダーを示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | 見出しをクローンします。 |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | すべてのセグメントを持つ見出しをクローンします。 |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | 指定された部分の [`TextFragment`](../../aspose.pdf.text/textfragment/) テキストを表す [`TextSegment`](../../aspose.pdf.text/textsegment/) を取得します。 |

### 参照

* クラス [TextFragment](../../aspose.pdf.text/textfragment/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)