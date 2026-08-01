---
title: "クラス TextSegment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextSegment クラス。Pdf テキストのセグメントを表します"
type: docs
weight: 11240
url: /ja/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Pdf テキストのセグメントを表します。

```csharp
public sealed class TextSegment
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | TextSegment オブジェクトを作成します。 |
| [TextSegment](textsegment/#constructor_1)(string) | TextSegment オブジェクトを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | `TextSegment` オブジェクトで表されるテキストの位置を取得します。Position 構造体の YIndent はテキストセグメントのベースライン座標を表します。 |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | テキストセグメント内の文字情報を表す CharInfo オブジェクトのコレクションを取得します。 |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | 表示テキスト演算子 (Tj, TJ) セグメントにおける現在のセグメントの終了文字インデックスを取得します。 |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | セグメントのハイパーリンク（pdf ジェネレータ用）を取得または設定します。 |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | `TextSegment` オブジェクトで表されるテキストの位置を取得します。 |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | TextSegment の矩形を取得します。 |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | 表示テキスト演算子 (Tj, TJ) セグメントにおける現在のセグメントの開始文字インデックスを取得します。 |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | `TextSegment` オブジェクトが表す文字列テキストオブジェクトを取得または設定します。 |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。 |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | `TextSegment` オブジェクトが表すテキストのテキスト状態を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | 文字列を HTML としてエンコードします。 |

## 備考

簡単に言うと、`TextSegment` オブジェクトは [`TextFragment`](../textfragment/) オブジェクトの子です。詳細としては、Pdf ドキュメントのテキストは二つの基本オブジェクト、[`TextFragment`](../textfragment/) と `TextSegment` によって表現されます。両者の違いは主にコンテキストに依存します。以下のシナリオを考えてみましょう。ユーザーがテキスト \"hello world\" を検索し、そのテキストを操作したり、プロパティを変更したり、表示したりします。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

PDF テキストの物理的な表現は非常に複雑です。テキスト \"hello world\" は、いくつかの物理的に独立したテキストセグメントで構成されることがあります。Aspose.Pdf テキストモデルは基本的に、[`TextFragment`](../textfragment/) オブジェクトがユーザーのクエリを表す物理的な `TextSegment` オブジェクトの集合に対して単一の論理操作セットを提供することを定義しています。テキスト検索シナリオでは、[`TextFragment`](../textfragment/) は論理的な \"hello world\" テキスト表現であり、`TextSegment` オブジェクトのコレクションは \"hello world\" テキストオブジェクトを構成するすべての物理的セグメントを表します。したがって、[`TextFragment`](../textfragment/) は論理テキスト表現に近く、`TextSegment` は物理テキスト表現に近いです。明らかに各 `TextSegment` オブジェクトはそれぞれ独自のフォント、カラー、位置プロパティを持つことができます。[`TextFragment`](../textfragment/) はフォントの設定、フォントサイズの設定、フォントカラーの設定など、テキストのプロパティを簡単に変更する方法を提供します。一方、`TextSegment` オブジェクトは個別にアクセス可能で、ユーザーは `TextSegment` オブジェクトを独立して操作できます。

## 例

この例では、`TextSegment` オブジェクトの [`TextState`](./textstate/) オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現の最初のテキストセグメントの前景色を変更します
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 最初のテキスト出現の最初のテキストセグメントのフォントサイズを変更します
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


