---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment クラス。Pdf テキストのセグメントを表します
type: docs
weight: 11050
url: /ja/net/aspose.pdf.text/textsegment/
---
## TextSegment クラス

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
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | テキストセグメント内の文字に関する情報を表す CharInfo オブジェクトのコレクションを取得します。 |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | 現在のセグメントの終了文字インデックスを取得します（表示テキスト演算子 (Tj, TJ) セグメント内）。 |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | セグメントのハイパーリンクを取得または設定します（PDF ジェネレーター用）。 |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | `TextSegment` オブジェクトで表されるテキストの位置を取得します。 |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | TextSegment の矩形を取得します。 |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | 現在のセグメントの開始文字インデックスを取得します（表示テキスト演算子 (Tj, TJ) セグメント内）。 |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | `TextSegment` オブジェクトが表す文字列テキストオブジェクトを取得または設定します。 |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで書き込めない場合の特別な動作を定義します。 |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | `TextSegment` オブジェクトが表すテキストのテキスト状態を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | 文字列を HTML としてエンコードします。 |

## 備考

簡単に言うと、`TextSegment` オブジェクトは [`TextFragment`](../textfragment/) オブジェクトの子です。詳細には：Pdf ドキュメントのテキストは、基本的に二つのオブジェクトによって表されます：[`TextFragment`](../textfragment/) と `TextSegment`。それらの違いは主にコンテキスト依存です。次のシナリオを考えてみましょう。ユーザーがテキスト "hello world" を検索して、それを操作したり、プロパティを変更したり、見るなどします。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

物理的に Pdf テキストの表現は非常に複雑です。テキスト "hello world" は、いくつかの物理的に独立したテキストセグメントで構成される場合があります。Aspose.Pdf テキストモデルは基本的に、[`TextFragment`](../textfragment/) オブジェクトがユーザーのクエリを表す物理的な `TextSegment` オブジェクトのセットに対して単一の論理操作セットを提供することを確立します。テキスト検索シナリオでは、[`TextFragment`](../textfragment/) は論理的な "hello world" テキスト表現であり、`TextSegment` オブジェクトのコレクションは "hello world" テキストオブジェクトを構成するすべての物理セグメントを表します。したがって、[`TextFragment`](../textfragment/) は論理テキスト表現に近いです。そして `TextSegment` は物理テキスト表現に近いです。明らかに、各 `TextSegment` オブジェクトは独自のフォント、色、配置プロパティを持つことができます。[`TextFragment`](../textfragment/) は、フォントを設定したり、フォントサイズを設定したり、フォントカラーを設定したりするなど、テキストとそのプロパティを変更する簡単な方法を提供します。一方、`TextSegment` オブジェクトはアクセス可能であり、ユーザーは `TextSegment` オブジェクトを独立して操作できます。

## 例

この例は、`TextSegment` オブジェクトの [`TextState`](./textstate/) オブジェクトを使用して、テキストの色とフォントサイズを変更する方法を示しています。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)