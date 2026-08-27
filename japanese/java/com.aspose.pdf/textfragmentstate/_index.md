---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> テキストフラグメントのテキスト状態を表します。 </p> <hr> <pre> この例は、{@code TextState} オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。 // Open."
type: docs
weight: 5150
url: /ja/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> テキストフラグメントのテキスト状態を表します。 </p> <hr> <pre> この例は、{@code TextState} オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキストの以下のプロパティを変更する方法を提供します： font ({@code TextFragmentState.Font} property) font size ({@code TextFragmentState.FontSize} property) font style ( {@code TextFragmentState.FontStyle} property) foreground color ( {@code TextFragmentState.ForegroundColor} property) background color ( {@code TextFragmentState.BackgroundColor} property) <p> {@code TextFragmentState} のプロパティを変更すると、{@code TextFragment.Segments} コレクションが変更される可能性があることに注意してください。TextFragment は集約オブジェクトであり、内部セグメントを再配置したり単一のセグメントに結合したりすることがあります。{@code TextFragment.Segments} コレクションを変更せずに保持する必要がある場合は、内部セグメントを個別に変更してください。 </p> @see TextFragmentAbsorber @see IDocument

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | 指定された {@code TextFragment} オブジェクトを使用して {@code TextFragmentState} オブジェクトの新しいインスタンスを初期化します。この {@code TextFragmentState} の初期化はサポートされていません。TextFragmentState は {@code TextFragment.TextState} プロパティでのみ利用可能です。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> 別の textState から設定を適用します </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | 別の textState から設定を適用します |
| [getBackgroundColor](#getBackgroundColor--) | {@code TextFragment} オブジェクトで表されるテキストの背景色を設定します |
| [getCharacterSpacing](#getCharacterSpacing--) | {@code TextFragment} オブジェクトで表されるテキストの文字間隔を取得します。 |
| [getCoordinateOrigin](#getCoordinateOrigin--) | テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。 |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | テキスト矩形の枠線が描画されるかどうかのフラグを取得します。 |
| [getFont](#getFont--) | {@code TextFragment} オブジェクトで表されるテキストのフォントを取得します |
| [getFontSize](#getFontSize--) | {@code TextFragment} オブジェクトで表されるテキストのフォントサイズを取得します |
| [getFontStyle](#getFontStyle--) | {@code TextFragment} オブジェクトで表されるテキストのフォントスタイルを設定します |
| [getForegroundColor](#getForegroundColor--) | {@code TextFragment} オブジェクトで表されるテキストの前景色を取得します |
| [getFormattingOptions](#getFormattingOptions--) | 書式設定オプションを取得または設定します。オプションの設定はジェネレーターシナリオでのみ有効です。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> テキストの水平揃えを取得します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextFragmentState.VerticalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | {@code TextFragment} オブジェクトで表されるテキストの水平スケーリングを取得します。 |
| [getLineSpacing](#getLineSpacing--) | <p> テキストの行間を取得します。 </p> |
| [getRenderingMode](#getRenderingMode--) | テキストのレンダリングモードを取得または設定します。 |
| [getRotation](#getRotation--) | 回転角度（度単位）を取得または設定します。 |
| [getStrokingColor](#getStrokingColor--) | 取得または設定します {@code TextFragment} のレンダリングにおけるカラー ストローク操作（テキストのストローク、矩形の枠） |
| [getTabStops](#getTabStops--) | <p> テキストのタブストップを取得します。 </p> <hr> <p> Tabstops プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。Tabstops は {@code TextFragment} の初期化中に追加でき、テキストの前に構築する必要があります。 </p> |
| [getTextHeight](#getTextHeight--) | テキストの高さを取得します（{@code TextFragment} オブジェクトで表されます） |
| [getWordSpacing](#getWordSpacing--) | テキストの単語間隔を取得します。 |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | 入力文字列が定義された矩形内に配置できるかどうかをチェックします。 |
| [isInvisible](#isInvisible--) | テキストの不可視性を取得します。 |
| [isStrikeOut](#isStrikeOut--) | テキストの取り消し線を取得または設定します（{@link TextFragment} オブジェクトで表されます） |
| [isSubscript](#isSubscript--) | テキストの下付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。 |
| [isSuperscript](#isSuperscript--) | テキストの上付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。 |
| [isUnderline](#isUnderline--) | テキストの下線を取得または設定します（{@link TextFragment} オブジェクトで表されます） |
| [measureHeight](#measureHeight-char-) | 文字の高さを測定します。 |
| [measureString](#measureString-java.lang.String-) | 文字列を測定します。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | テキストの背景色を設定します（TextFragment オブジェクトで表されます） |
| [setCharacterSpacing](#setCharacterSpacing-float-) | テキストの文字間隔を設定します（{@code TextFragment} オブジェクトで表されます）。 |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。 |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | テキスト矩形の枠線が描画されるかどうかのフラグを設定します。 |
| [setFont](#setFont-com.aspose.pdf.Font-) | テキストのフォントを設定します（{@code TextFragment} オブジェクトで表されます） |
| [setFontSize](#setFontSize-float-) | テキストのフォントサイズを設定します（{@code TextFragment} オブジェクトで表されます） |
| [setFontStyle](#setFontStyle-int-) | テキストのフォントスタイルを設定します（{@link TextFragment} オブジェクトで表されます） |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | テキストの前景色を設定します（{@code TextFragment} オブジェクトで表されます） |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | 書式設定オプションを取得または設定します。オプションの設定はジェネレーターシナリオでのみ有効です。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> テキストの水平揃えを設定します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextFragmentState.VerticalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | テキストの水平スケーリングを設定します（{@code TextFragment} オブジェクトで表されます）。 |
| [setInvisible](#setInvisible-boolean-) | テキストの不可視性を設定します。 |
| [setLineSpacing](#setLineSpacing-float-) | <p> テキストの行間を設定します。 </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | テキストのレンダリングモードを取得または設定します。 |
| [setRotation](#setRotation-double-) | 回転角度（度単位）を取得または設定します。 |
| [setStrikeOut](#setStrikeOut-boolean-) | テキストの取り消し線を設定します。これは {@code TextFragment} オブジェクトで表されます。 |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | 取得または設定します {@code TextFragment} のレンダリングにおけるカラー ストローク操作（テキストのストローク、矩形の枠） |
| [setSubscript](#setSubscript-boolean-) | テキストの下付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。 |
| [setSuperscript](#setSuperscript-boolean-) | テキストの上付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。 |
| [setUnderline](#setUnderline-boolean-) | テキストの下線を設定します。{@code TextFragment} オブジェクトで表されます |
| [setWordSpacing](#setWordSpacing-float-) | テキストの単語間隔を設定します。 |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
指定された {@code TextFragment} オブジェクトを使用して {@code TextFragmentState} オブジェクトの新しいインスタンスを初期化します。この {@code TextFragmentState} の初期化はサポートされていません。TextFragmentState は {@code TextFragment.TextState} プロパティでのみ利用可能です。

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> 別の textState から設定を適用します </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
別の textState から設定を適用します

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

{@code TextFragment} オブジェクトで表されるテキストの背景色を設定します

**Returns:**
値 Color オブジェクト

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

{@code TextFragment} オブジェクトで表されるテキストの文字間隔を取得します。

**Returns:**
float 値

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。

**Returns:**
CoordinateOrigin 要素

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

テキスト矩形の枠線が描画されるかどうかのフラグを取得します。

**Returns:**
ブール値

### getFont {#getFont--}
```
public Font getFont()
```

{@code TextFragment} オブジェクトで表されるテキストのフォントを取得します

**Returns:**
フォント値

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

{@code TextFragment} オブジェクトで表されるテキストのフォントサイズを取得します

**Returns:**
float 値

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

{@code TextFragment} オブジェクトで表されるテキストのフォントスタイルを設定します

**Returns:**
FontStyles 要素 @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

{@code TextFragment} オブジェクトで表されるテキストの前景色を取得します

**Returns:**
Color オブジェクト

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

書式設定オプションを取得または設定します。オプションの設定はジェネレーターシナリオでのみ有効です。

**Returns:**
TextFormattingOptions インスタンス

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> テキストの水平揃えを取得します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextFragmentState.VerticalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p>

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

{@code TextFragment} オブジェクトで表されるテキストの水平スケーリングを取得します。

**Returns:**
float 値

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> テキストの行間を取得します。 </p>

**Returns:**
float 値 <hr> <p> この値はドキュメント内のテキスト特性として保持されないことに注意してください。LineSpacing プロパティの getter は、対象オブジェクトに対して以前に LineSpacing setter で明示的に設定されている場合に機能します。このプロパティは、現在の生成/変更プロセスのコンテキストでランタイムによって使用されます。 </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

テキストのレンダリングモードを取得または設定します。

**Returns:**
TextRenderingMode 要素

### getRotation {#getRotation--}
```
public double getRotation()
```

回転角度（度単位）を取得または設定します。

**Returns:**
double 値

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

取得または設定します {@code TextFragment} のレンダリングにおけるカラー ストローク操作（テキストのストローク、矩形の枠）

**Returns:**
Color インスタンス

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> テキストのタブストップを取得します。 </p> <hr> <p> Tabstops プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。Tabstops は {@code TextFragment} の初期化中に追加でき、テキストの前に構築する必要があります。 </p>

**Returns:**
TabStops オブジェクト

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

テキストの高さを取得します（{@code TextFragment} オブジェクトで表されます）

**Returns:**
float 値

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

テキストの単語間隔を取得します。

**Returns:**
float 値

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
入力文字列が定義された矩形内に配置できるかどうかをチェックします。

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

テキストの不可視性を取得します。

**Returns:**
ブール値

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

テキストの取り消し線を取得または設定します（{@link TextFragment} オブジェクトで表されます）

**Returns:**
ブール値

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

テキストの下付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。

**Returns:**
ブール値

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

テキストの上付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。

**Returns:**
value ブール値

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

テキストの下線を取得または設定します（{@link TextFragment} オブジェクトで表されます）

**Returns:**
ブール値

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
```

文字の高さを測定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 文字 |  | 測定対象の文字。 |

**Returns:**
フォントから取得できる場合の文字の高さ。取得できない場合は 0。

### measureString {#measureString-java.lang.String-}
文字列を測定します。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
テキストの背景色を設定します（TextFragment オブジェクトで表されます）

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

テキストの文字間隔を設定します（{@code TextFragment} オブジェクトで表されます）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

テキスト矩形の枠線が描画されるかどうかのフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFont {#setFont-com.aspose.pdf.Font-}
テキストのフォントを設定します（{@code TextFragment} オブジェクトで表されます）

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

テキストのフォントサイズを設定します（{@code TextFragment} オブジェクトで表されます）

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

テキストのフォントスタイルを設定します（{@link TextFragment} オブジェクトで表されます）

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
テキストの前景色を設定します（{@code TextFragment} オブジェクトで表されます）

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
書式設定オプションを取得または設定します。オプションの設定はジェネレーターシナリオでのみ有効です。

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> テキストの水平揃えを設定します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextFragmentState.VerticalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

テキストの水平スケーリングを設定します（{@code TextFragment} オブジェクトで表されます）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

テキストの不可視性を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> テキストの行間を設定します。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 <hr> <p> この値はドキュメント内のテキスト特性として保持されないことに注意してください。LineSpacing プロパティの getter は、対象オブジェクトに対して以前に LineSpacing setter で明示的に設定されている場合に機能します。このプロパティは、現在の生成/変更プロセスのコンテキストでランタイムによって使用されます。 </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
テキストのレンダリングモードを取得または設定します。

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

回転角度（度単位）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

テキストの取り消し線を設定します。これは {@code TextFragment} オブジェクトで表されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
取得または設定します {@code TextFragment} のレンダリングにおけるカラー ストローク操作（テキストのストローク、矩形の枠）

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

テキストの下付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

テキストの上付き文字を取得または設定します（{@code TextFragment} オブジェクトで表されます）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

テキストの下線を設定します。{@code TextFragment} オブジェクトで表されます

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

テキストの単語間隔を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |
