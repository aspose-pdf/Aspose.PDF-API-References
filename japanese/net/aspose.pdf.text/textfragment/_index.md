---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragment クラス。Pdf テキストのフラグメントを表します
type: docs
weight: 10940
url: /ja/net/aspose.pdf.text/textfragment/
---
## TextFragment クラス

Pdf テキストのフラグメントを表します。

```csharp
public class TextFragment : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | `TextFragment` オブジェクトの新しいインスタンスを初期化します。 |
| [TextFragment](textfragment/#constructor_2)(string) | 単一の [`TextSegment`](../textsegment/) オブジェクトを含む `TextFragment` オブジェクトを作成します。セグメント内のテキスト文字列を指定します。 |
| [TextFragment](textfragment/#constructor_1)(TabStops) | 事前定義された [`TabStops`](../tabstops/) 位置を持つ `TextFragment` オブジェクトの新しいインスタンスを初期化します。 |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | 単一の [`TextSegment`](../textsegment/) オブジェクトを含み、事前定義された [`TabStops`](../tabstops/) 位置を持つ `TextFragment` オブジェクトを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | `TextFragment` オブジェクトで表されるテキストの位置を取得または設定します。Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。 |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 段落のエンドノートを取得または設定します。(PDF 生成専用) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 段落のフットノートを取得または設定します。(PDF 生成専用) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment を含むフォームオブジェクトを取得します |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | テキストフラグメントの水平配置を取得または設定します。 |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | フラグメントのハイパーリンクを設定します |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。(PDF 生成用) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側のマージンを取得または設定します。(PDF 生成用) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment を含むページを取得します |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | `TextFragment` オブジェクトで表されるテキストの位置を取得または設定します。 |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment の矩形を取得します |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | テキスト置換オプションを取得します。オプションは、フラグメントテキストが短く/長く置き換えられるときの動作を定義します。 |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 現在の `TextFragment` のテキストセグメントを取得または設定します。 |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | `TextFragment` オブジェクトが表す文字列テキストオブジェクトを取得または設定します。 |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで書き込めない場合の特別な動作を定義します。 |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | `TextFragment` オブジェクトが表すテキストのテキスト状態を取得または設定します。 |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | テキストフラグメントの垂直配置を取得または設定します。 |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | この段落のラップ行数を取得または設定します。(PDF 生成専用) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を持つことができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | フラグメントをクローンします。 |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | すべてのセグメントを持つフラグメントをクローンします。 |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | 指定された部分の `TextFragment` テキストを表す [`TextSegment`](../textsegment/) を取得します。 |

## 備考

簡単に言うと、`TextFragment` オブジェクトは [`TextSegment`](../textsegment/) オブジェクトのリストを含みます。詳細には：Pdf 文書のテキストは、`TextFragment` と [`TextSegment`](../textsegment/) の二つの基本オブジェクトで表されます。これらの違いは主にコンテキストに依存します。次のシナリオを考えてみましょう。ユーザーがテキスト "hello world" を検索して、それを操作したり、プロパティを変更したり、見るなどします。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

物理的に Pdf テキストの表現は非常に複雑です。"hello world" というテキストは、いくつかの物理的に独立したテキストセグメントで構成される場合があります。Aspose.Pdf テキストモデルは基本的に、`TextFragment` オブジェクトがユーザーのクエリを表す物理 [`TextSegment`](../textsegment/) オブジェクトセットに対して単一の論理操作セットを提供することを確立します。テキスト検索シナリオでは、`TextFragment` は論理的な "hello world" テキスト表現であり、[`TextSegment`](../textsegment/) オブジェクトコレクションは "hello world" テキストオブジェクトを構成するすべての物理セグメントを表します。したがって、`TextFragment` は論理テキスト表現に近いです。そして [`TextSegment`](../textsegment/) は物理テキスト表現に近いです。明らかに、各 [`TextSegment`](../textsegment/) オブジェクトは独自のフォント、色、位置プロパティを持つ場合があります。`TextFragment` は、そのプロパティを持つテキストを変更する簡単な方法を提供します：フォントを設定し、フォントサイズを設定し、フォントカラーを設定するなどです。一方、[`TextSegment`](../textsegment/) オブジェクトはアクセス可能であり、ユーザーは独立して [`TextSegment`](../textsegment/) オブジェクトを操作できます。`TextFragment` プロパティを変更すると、内部の [`Segments`](./segments/) コレクションが変更される場合があることに注意してください。なぜなら、TextFragment は集約オブジェクトであり、内部セグメントを再配置したり、単一のセグメントに統合したりする可能性があるからです。[`Segments`](./segments/) コレクションを変更せずに保持する必要がある場合は、内部セグメントを個別に変更してください。

## 例

この例は、最初の PDF ドキュメントページでテキストを見つけ、そのテキストとフォントを置き換える方法を示しています。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* クラス [BaseParagraph](../../aspose.pdf/baseparagraph/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)