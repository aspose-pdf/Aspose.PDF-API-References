---
title: "クラス TextFragment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextFragment クラス。Pdf テキストのフラグメントを表します"
type: docs
weight: 11120
url: /ja/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Pdf テキストのフラグメントを表します。

```csharp
public class TextFragment : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | `TextFragment` オブジェクトの新しいインスタンスを初期化します。 |
| [TextFragment](textfragment/#constructor_2)(string) | 単一の [`TextSegment`](../textsegment/) オブジェクトを内部に持つ `TextFragment` オブジェクトを作成します。セグメント内のテキスト文字列を指定します。 |
| [TextFragment](textfragment/#constructor_1)(TabStops) | 事前定義された [`TabStops`](../tabstops/) 位置を使用して `TextFragment` オブジェクトの新しいインスタンスを初期化します。 |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | 単一の [`TextSegment`](../textsegment/) オブジェクトを内部に持ち、事前定義された [`TabStops`](../tabstops/) 位置を設定した `TextFragment` オブジェクトを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | `TextFragment` オブジェクトで表されるテキストの位置を取得します。Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。 |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 段落の末尾ノートを取得または設定します。（PDF 生成時のみ） |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 段落のフットノートを取得または設定します。（PDF 生成時のみ） |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment を含むフォームオブジェクトを取得します |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | テキストフラグメントの水平揃えを取得または設定します。 |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | フラグメントのハイパーリンクを設定します |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment を含むページを取得します |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | `TextFragment` オブジェクトで表されるテキストの位置を取得または設定します。 |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment の矩形を取得します |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | テキスト置換オプションを取得します。オプションはフラグメントテキストが短くまたは長く置換される際の動作を定義します。 |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 現在の `TextFragment` のテキストセグメントを取得します。 |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | `TextFragment` オブジェクトが表す文字列テキストオブジェクトを取得または設定します。 |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。 |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | `TextFragment` オブジェクトが表すテキストのテキスト状態を取得または設定します。 |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | テキストフラグメントの垂直揃えを取得または設定します。 |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | この段落の折り返し行数を取得または設定します。（PDF 生成時のみ） |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | フラグメントを複製します。 |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | すべてのセグメントを含むフラグメントを複製します。 |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | 指定された `TextFragment` テキストの一部を表す [`TextSegment`](../textsegment/)(s) を取得します。 |

## 備考

簡単に言えば、`TextFragment` オブジェクトは [`TextSegment`](../textsegment/) オブジェクトのリストを保持しています。詳細としては、Pdf の PDF 文書のテキストは 2 つの基本オブジェクト、`TextFragment` と [`TextSegment`](../textsegment/) によって表現されます。両者の違いは主にコンテキストに依存します。次のシナリオを考えてみましょう。ユーザーがテキスト "hello world" を検索し、それを操作したり、プロパティを変更したり、表示したりします。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

PDF テキストの物理的な表現は非常に複雑です。テキスト "hello world" は、いくつかの物理的に独立したテキストセグメントで構成されることがあります。Aspose.Pdf のテキストモデルは基本的に、`TextFragment` オブジェクトがユーザーのクエリを表す物理的な [`TextSegment`](../textsegment/) オブジェクトの集合に対して単一の論理操作セットを提供することを定義しています。テキスト検索シナリオでは、`TextFragment` は論理的な "hello world" テキスト表現であり、[`TextSegment`](../textsegment/) オブジェクトのコレクションは "hello world" テキストオブジェクトを構成するすべての物理的セグメントを表します。したがって、`TextFragment` は論理テキスト表現に近く、[`TextSegment`](../textsegment/) は物理テキスト表現に近いです。明らかに各 [`TextSegment`](../textsegment/) オブジェクトはそれぞれ独自のフォント、カラー、位置プロパティを持つことができます。`TextFragment` はフォントの設定、フォントサイズの設定、フォントカラーの設定など、テキストとそのプロパティを簡単に変更する方法を提供します。一方、[`TextSegment`](../textsegment/) オブジェクトは個別にアクセス可能で、ユーザーは [`TextSegment`](../textsegment/) オブジェクトを独立して操作できます。`TextFragment` のプロパティを変更すると、`TextFragment` が集約オブジェクトであり内部セグメントを再配置したり単一セグメントに結合したりする可能性があるため、内部の [`Segments`](./segments/) コレクションが変更されることに注意してください。[`Segments`](./segments/) コレクションを変更せずに残したい場合は、内部セグメントを個別に変更してください。

## 例

この例では、最初の PDF 文書ページでテキストを検索し、そのテキストとフォントを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のテキストとフォントを変更します
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


