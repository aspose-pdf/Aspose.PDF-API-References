---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> Pdf テキストのフラグメントを表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストとフォントを置換する方法を示しています。 // Open document.</pre>"
type: docs
weight: 5110
url: /ja/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> PDF テキストのフラグメントを表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストとフォントを置換する方法を示します。 // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> 簡潔に言うと、{@code TextFragment} オブジェクトは {@code TextSegment} オブジェクトのリストを保持します。 詳細は次のとおりです。 {@code com.aspose.pdf} の PDF ドキュメントのテキストは、{@code TextFragment} と {@code TextSegment} の 2 つの基本オブジェクトで表現されます。 それらの違いは主にコンテキストに依存します。 以下のシナリオを考えてみましょう。 ユーザーはテキスト "hello world" を検索し、操作やプロパティ変更、参照などを行います。 Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> PDF テキストの物理的な表現は非常に複雑です。テキスト "hello world" は、いくつかの物理的に独立したテキストセグメントで構成される場合があります。Aspose.Pdf のテキストモデルは基本的に、{@code TextFragment} オブジェクトがユーザーのクエリを表す物理的 {@code TextSegment} オブジェクトの集合に対して単一の論理操作セットを提供することを示しています。テキスト検索シナリオでは、{@code TextFragment} は論理的な "hello world" テキスト表現であり、{@code TextSegment} オブジェクトのコレクションは "hello world" テキストオブジェクトを構成するすべての物理的セグメントを表します。したがって、{@code TextFragment} は論理テキスト表現に近く、{@code TextSegment} は物理テキスト表現に近いです。明らかに各 {@code TextSegment} オブジェクトはそれぞれ独自のフォント、色、位置プロパティを持つことができます。{@code TextFragment} はフォントの設定、フォントサイズの設定、フォントカラーの設定など、テキストのプロパティを簡単に変更する方法を提供します。一方、{@code TextSegment} オブジェクトは個別にアクセス可能で、ユーザーは {@code TextSegment} オブジェクトを独立して操作できます。 <p> TextFragment のプロパティを変更すると、TextFragment が集約オブジェクトであり、内部セグメントを再配置したり単一のセグメントに結合したりするため、内部 {@code Segments} コレクションが変更される可能性があることに注意してください。{@code Segments} コレクションを変更せずに保持する必要がある場合は、内部セグメントを個別に変更してください。 </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextFragment](#TextFragment--) | 新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。 |
| [TextFragment](#TextFragment-java.lang.String-) | 新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。 |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | 新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。 |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | 新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | すべてのセグメントを含むフラグメントをクローンします。 |
| [deepClone](#deepClone--) | フラグメントをクローンします。 |
| [getBaselinePosition](#getBaselinePosition--) | テキストの位置を取得します（{@code TextFragment} オブジェクトで表されます）。Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。 |
| [getEndNote](#getEndNote--) | 段落のエンドノートを取得します。（PDF 生成専用） |
| [getFootNote](#getFootNote--) | 段落のフットノートを取得します。（PDF 生成専用） |
| [getForm](#getForm--) | TextFragment を含むフォームオブジェクトを取得します。TextFragment オブジェクトがフォームに属さない場合、値は null になる可能性があります。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | テキストフラグメントの水平揃えを取得します。 |
| [getPage](#getPage--) | TextFragment を含むページを取得します。TextFragment オブジェクトがいずれのページにも属さない場合、値は null になる可能性があります。 |
| [getPosition](#getPosition--) | <p> テキストの位置を取得します（{@code TextFragment} オブジェクトで表されます）。 </p> |
| [getRectangle](#getRectangle--) | TextFragment の矩形を取得します。 |
| [getReplaceOptions](#getReplaceOptions--) | テキスト置換オプションを取得します。オプションは、フラグメントテキストが短くまたは長く置換される際の動作を定義します。 |
| [getSegments](#getSegments--) | <p> 現在の {@code TextFragment} のテキストセグメントを取得します。 </p> |
| [getText](#getText--) | <p> {@code TextFragment} オブジェクトが表す {@code string} テキストオブジェクトを取得します。 </p> |
| [getTextEditOptions](#getTextEditOptions--) | テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。 |
| [getTextState](#getTextState--) | <p> {@code TextFragment} オブジェクトが表すテキストの状態を取得または設定します。 </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | テキストフラグメントの垂直揃えを取得します。 |
| [getWrapLinesCount](#getWrapLinesCount--) | この段落の折り返し行数を取得します（PDF 生成専用）。 |
| [isolateTextSegments](#isolateTextSegments-int-int-) | 指定された {@code TextFragment} テキストの部分を表す {@code TextSegment} を取得します。 |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | テキストの位置を設定します（{@code TextFragment} オブジェクトで表現）。Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。 |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | 段落のエンドノートを設定します。（PDF 生成時のみ） |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | 段落のフットノートを設定します。（PDF 生成時のみ） |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | テキストフラグメントの水平配置を設定します。 |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | フラグメントのハイパーリンクを設定します。 |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> テキストの位置を設定します（{@code TextFragment} オブジェクトで表現）。 </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | TextFragment の矩形を取得します。 |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | setSegments メソッドを表します。 |
| [setText](#setText-java.lang.String-) | <p> {@code TextFragment} オブジェクトが表す {@code string} テキストオブジェクトを設定します。 </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | テキストフラグメントの垂直配置を設定します。 |
| [setWrapLinesCount](#setWrapLinesCount-int-) | この段落の折り返し行数を設定します（PDF 生成時のみ）。 |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。

### TextFragment {#TextFragment-java.lang.String-}
新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
新しい {@code TextFragment} オブジェクトのインスタンスを初期化します。

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

すべてのセグメントを含むフラグメントをクローンします。

**Returns:**
クローンされたオブジェクト

### deepClone {#deepClone--}
```
public Object deepClone()
```

フラグメントをクローンします。

**Returns:**
クローンされたオブジェクト

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

テキストの位置を取得します（{@code TextFragment} オブジェクトで表されます）。Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。

**Returns:**
位置の値

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

段落のエンドノートを取得します。（PDF 生成専用）

**Returns:**
ノート値

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

段落のフットノートを取得します。（PDF 生成専用）

**Returns:**
ノート値

### getForm {#getForm--}
```
public XForm getForm()
```

TextFragment を含むフォームオブジェクトを取得します。TextFragment オブジェクトがフォームに属さない場合、値は null になる可能性があります。

**Returns:**
XForm 値

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

テキストフラグメントの水平揃えを取得します。

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

TextFragment を含むページを取得します。TextFragment オブジェクトがいずれのページにも属さない場合、値は null になる可能性があります。

**Returns:**
Page オブジェクト

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> テキストの位置を取得します（{@code TextFragment} オブジェクトで表されます）。 </p>

**Returns:**
位置値 <hr> <pre> この例は、{@code TextFragment} オブジェクトで表現されたテキストの配置を表示する方法を示しています。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

TextFragment の矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

テキスト置換オプションを取得します。オプションは、フラグメントテキストが短くまたは長く置換される際の動作を定義します。

**Returns:**
TextReplaceOptions インスタンス

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> 現在の {@code TextFragment} のテキストセグメントを取得します。 </p>

**Returns:**
TextSegmentCollection 値 <hr> <pre> この例は、{@code TextFragment} 内のすべての {@code TextSegment} オブジェクトをナビゲートする方法を示しています。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and out their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> 簡単に言えば、{@code TextSegment} オブジェクトは {@code TextFragment} オブジェクトの子です。上級ユーザーはセグメントに直接アクセスして、より複雑なテキスト編集シナリオを実行できます。詳細については、{@code TextFragment} オブジェクトの説明をご覧ください。 </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> {@code TextFragment} オブジェクトが表す {@code string} テキストオブジェクトを取得します。 </p>

**Returns:**
文字列値 <hr> <pre> この例は、テキストを検索し、{@code TextFragment} オブジェクトで表される最初の出現箇所を置換する方法を示しています。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。

**Returns:**
TextEditOptions インスタンス

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> {@code TextFragment} オブジェクトが表すテキストの状態を取得または設定します。 </p>

**Returns:**
TextFragmentState オブジェクト <hr> <pre> この例は、{@code TextState} オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキストの以下のプロパティを変更する方法を提供します：Font、FontSize、FontStyle、ForegroundColor、BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

テキストフラグメントの垂直揃えを取得します。

**Returns:**
int 値 @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

この段落の折り返し行数を取得します（PDF 生成専用）。

**Returns:**
int 値です。

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

指定された {@code TextFragment} テキストの部分を表す {@code TextSegment} を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex |  | 新しい {@code TextSegment} が開始するテキスト内の位置。 |
| 長さ |  | {@code TextSegment} に分割されるテキストの長さ。 |

**Returns:**
{@code TextSegmentCollection} は、指定された位置で開始し、指定された長さを持つテキスト部分文字列を表すテキストセグメントを含みます。

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
テキストの位置を設定します（{@code TextFragment} オブジェクトで表現）。Position 構造体の YIndent はテキストフラグメントのベースライン座標を表します。

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
段落のエンドノートを設定します。（PDF 生成時のみ）

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
段落のフットノートを設定します。（PDF 生成時のみ）

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
テキストフラグメントの水平配置を設定します。

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
フラグメントのハイパーリンクを設定します。

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> テキストの位置を設定します（{@code TextFragment} オブジェクトで表現）。 </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
TextFragment の矩形を取得します。

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
setSegments メソッドを表します。

### setText {#setText-java.lang.String-}
<p> {@code TextFragment} オブジェクトが表す {@code string} テキストオブジェクトを設定します。 </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
テキストフラグメントの垂直配置を設定します。

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

この段落の折り返し行数を設定します（PDF 生成時のみ）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
