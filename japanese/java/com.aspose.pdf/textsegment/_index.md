---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> Pdf テキストのセグメントを表します。 </p> <hr> <pre> この例は、{@code TextState} オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています {@code"
type: docs
weight: 5300
url: /ja/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Pdf テキストのセグメントを表します。 </p> <hr> <pre> この例は、{@code TextState} オブジェクト（{@code TextSegment} オブジェクト）を使用してテキストの色とフォントサイズを変更する方法を示しています。 // ドキュメントを開く Document doc = new Document("D:\\Tests\\input.pdf"); // "hello world" のすべての出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 最初のページにアブソーバーを適用 doc.getPages().get(1).accept(absorber); // 最初のテキスト出現の最初のテキストセグメントの前景色を変更 absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // 最初のテキスト出現の最初のテキストセグメントのフォントサイズを変更 absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // ドキュメントを保存 doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> 簡単に言えば、{@code TextSegment} オブジェクトは {@code TextFragment} オブジェクトの子です。詳細としては、{@code Aspose.Pdf} の PDF ドキュメントのテキストは {@code TextFragment} と {@code TextSegment} の二つの基本オブジェクトで表現されます。両者の違いは主にコンテキストに依存します。以下のシナリオを考えてみましょう。ユーザーがテキスト "hello world" を検索し、操作やプロパティ変更、表示などを行います。Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> PDF テキストの物理的な表現は非常に複雑です。テキスト "hello world" は、いくつかの物理的に独立したテキストセグメントで構成されることがあります。Aspose.PDF のテキストモデルは、{@code TextFragment} オブジェクトがユーザーのクエリを表す物理的 {@code TextSegment} オブジェクトの集合に対して単一の論理操作セットを提供することを基本としています。テキスト検索シナリオでは、{@code TextFragment} は論理的な "hello world" テキスト表現であり、{@code TextSegment} オブジェクトのコレクションは "hello world" テキストオブジェクトを構成するすべての物理的セグメントを表します。したがって、{@code TextFragment} は論理テキスト表現に近く、{@code TextSegment} は物理テキスト表現に近いです。明らかに各 {@code TextSegment} オブジェクトは独自のフォント、カラー、位置プロパティを持つ可能性があります。{@code TextFragment} はフォント設定、フォントサイズ設定、フォントカラー設定など、プロパティを使用してテキストを簡単に変更する方法を提供します。一方、{@code TextSegment} オブジェクトは個別にアクセス可能で、ユーザーは {@code TextSegment} オブジェクトを独立して操作できます。</p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> TextSegment オブジェクトを作成します。 </p> <hr> <pre> この例は、テキストフラグメントオブジェクトを作成し、テキストフラグメントコレクションにテキストセグメントを追加して、PDF ページに追加する方法を示しています。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // テキストフラグメントを作成 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // テキストプロパティを設定 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // テキストフラグメントの Segments コレクションにもう一つセグメントを追加 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder オブジェクトを作成 TextBuilder builder = new TextBuilder(page); // テキストフラグメントを PDF ページに追加 builder.appendText(tf); // ドキュメントを保存 doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> TextSegment オブジェクトを作成します。 </p> <hr> <pre> この例は、テキストフラグメントオブジェクトを作成し、テキストフラグメントコレクションにテキストセグメントを追加して、PDF ページに追加する方法を示しています。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // テキストフラグメントを作成 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // テキストプロパティを設定 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // テキストフラグメントの Segments コレクションにもう一つセグメントを追加 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder オブジェクトを作成 TextBuilder builder = new TextBuilder(page); // テキストフラグメントを PDF ページに追加 builder.appendText(tf); // ドキュメントを保存 doc.save(outFile); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | {@code TextSegment} オブジェクトで表されるテキストの位置を取得します。Position 構造体の YIndent はテキストセグメントのベースライン座標を表します。 |
| [getCharacters](#getCharacters--) | テキストセグメント内の文字情報を表す CharInfo オブジェクトのコレクションを取得します。 |
| [getEndCharIndex](#getEndCharIndex--) | 表示テキスト演算子 (Tj, TJ) セグメントにおける現在のセグメントの終了文字インデックスを取得します。 |
| [getHyperlink](#getHyperlink--) | セグメントハイパーリンク（pdf generator 用）を取得または設定します。 |
| [getPosition](#getPosition--) | テキストの位置を取得します（{@code TextSegment} オブジェクトで表されます）。 |
| [getRectangle](#getRectangle--) | TextSegment の矩形を取得します。 |
| [getStartCharIndex](#getStartCharIndex--) | 表示テキスト演算子 (Tj, TJ) セグメント内の現在のセグメントの開始文字インデックスを取得します。 |
| [getText](#getText--) | {@code TextSegment} オブジェクトが表す {@code string} テキストオブジェクトを取得します。 |
| [getTextEditOptions](#getTextEditOptions--) | テキスト編集オプションを取得します。これらのオプションは、要求されたシンボルをフォントで書き込めない場合の特別な動作を定義します。 |
| [getTextState](#getTextState--) | <p> {@code TextSegment} オブジェクトが表すテキストの状態を取得または設定します。 </p> <hr> <p> テキストの次のプロパティを変更する方法を提供します: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | {@code TextSegment} オブジェクトで表されるテキストの位置を設定します。Position 構造体の YIndent はテキストセグメントのベースライン座標を表します。 |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | セグメントハイパーリンク（pdf generator 用）を取得または設定します。 |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | {@code TextSegment} オブジェクトで表されるテキストの位置を設定します。 |
| [setText](#setText-java.lang.String-) | {@code TextSegment} オブジェクトが表す {@code string} テキストオブジェクトを設定します。 |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | テキスト編集オプションを設定します。これらのオプションは、要求されたシンボルがフォントで表現できない場合の特別な動作を定義します。 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> {@code TextSegment} オブジェクトが表すテキストの状態を設定します。 </p> <hr> <p> テキストの次のプロパティを変更する方法を提供します: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | 抑制された更新で {@code TextSegment} オブジェクトが表す {@code string} テキストオブジェクトを設定します。 |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> TextSegment オブジェクトを作成します。 </p> <hr> <pre> この例は、テキストフラグメントオブジェクトを作成し、テキストフラグメントコレクションにテキストセグメントを追加して、PDF ページに追加する方法を示しています。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // テキストフラグメントを作成 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // テキストプロパティを設定 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // テキストフラグメントの Segments コレクションにもう一つセグメントを追加 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder オブジェクトを作成 TextBuilder builder = new TextBuilder(page); // テキストフラグメントを PDF ページに追加 builder.appendText(tf); // ドキュメントを保存 doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> TextSegment オブジェクトを作成します。 </p> <hr> <pre> この例は、テキストフラグメントオブジェクトを作成し、テキストフラグメントコレクションにテキストセグメントを追加して、PDF ページに追加する方法を示しています。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // テキストフラグメントを作成 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // テキストプロパティを設定 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // テキストフラグメントの Segments コレクションにもう一つセグメントを追加 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder オブジェクトを作成 TextBuilder builder = new TextBuilder(page); // テキストフラグメントを PDF ページに追加 builder.appendText(tf); // ドキュメントを保存 doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

{@code TextSegment} オブジェクトで表されるテキストの位置を取得します。Position 構造体の YIndent はテキストセグメントのベースライン座標を表します。

**Returns:**
位置の値

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

テキストセグメント内の文字情報を表す CharInfo オブジェクトのコレクションを取得します。

**Returns:**
CharInfoCollection オブジェクト

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

表示テキスト演算子 (Tj, TJ) セグメントにおける現在のセグメントの終了文字インデックスを取得します。

**Returns:**
int 値です。

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

セグメントハイパーリンク（pdf generator 用）を取得または設定します。

**Returns:**
Hyperlink オブジェクト

### getPosition {#getPosition--}
```
public Position getPosition()
```

テキストの位置を取得します（{@code TextSegment} オブジェクトで表されます）。

**Returns:**
位置の値

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

TextSegment の矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

表示テキスト演算子 (Tj, TJ) セグメント内の現在のセグメントの開始文字インデックスを取得します。

**Returns:**
int 値です。

### getText {#getText--}
```
public String getText()
```

{@code TextSegment} オブジェクトが表す {@code string} テキストオブジェクトを取得します。

**Returns:**
文字列値

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

テキスト編集オプションを取得します。これらのオプションは、要求されたシンボルをフォントで書き込めない場合の特別な動作を定義します。

**Returns:**
TextEditOptions 値

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> {@code TextSegment} オブジェクトが表すテキストの状態を取得または設定します。 </p> <hr> <p> テキストの次のプロパティを変更する方法を提供します: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
TextState の値

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
{@code TextSegment} オブジェクトで表されるテキストの位置を設定します。Position 構造体の YIndent はテキストセグメントのベースライン座標を表します。

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
セグメントハイパーリンク（pdf generator 用）を取得または設定します。

### setPosition {#setPosition-com.aspose.pdf.Position-}
{@code TextSegment} オブジェクトで表されるテキストの位置を設定します。

### setText {#setText-java.lang.String-}
{@code TextSegment} オブジェクトが表す {@code string} テキストオブジェクトを設定します。

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
テキスト編集オプションを設定します。これらのオプションは、要求されたシンボルがフォントで表現できない場合の特別な動作を定義します。

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> {@code TextSegment} オブジェクトが表すテキストの状態を設定します。 </p> <hr> <p> テキストの次のプロパティを変更する方法を提供します: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
抑制された更新で {@code TextSegment} オブジェクトが表す {@code string} テキストオブジェクトを設定します。
