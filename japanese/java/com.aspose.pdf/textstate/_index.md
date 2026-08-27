---
title: "TextState"
linktitle: "TextState"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストのテキスト状態を表します"
type: docs
weight: 5340
url: /ja/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

テキストのテキスト状態を表します

## フィールド

| フィールド | 説明 |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | デフォルトフォントのスペース文字幅におけるタブ設定のデフォルト値。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextState](#TextState--) | テキストステートオブジェクトを作成します。 |
| [TextState](#TextState-java.awt.Color-) | テキストステートオブジェクトを作成します。 |
| [TextState](#TextState-java.awt.Color-double-) | テキストステートオブジェクトを作成します。 |
| [TextState](#TextState-double-) | フォントサイズ指定付きのテキストステートオブジェクトを作成します。 |
| [TextState](#TextState-java.lang.String-) | テキストステートオブジェクトを作成します。 |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | テキストステートオブジェクトを作成します。 |
| [TextState](#TextState-java.lang.String-double-) | テキストステートオブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> 別の textState から設定を適用します </p> <hr> <p> 明示的に変更されたプロパティのみがコピーされます。 </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | 矩形のフォントサイズを計算します。 |
| [getBackgroundColor](#getBackgroundColor--) | <p> テキストの背景色を取得します。 </p> <hr> <p> この値はドキュメント内のテキスト特性として保持されないことに注意してください。BackgroundColor プロパティの getter は、対象オブジェクトに対して事前に BackgroundColor setter で明示的に設定されている場合に機能します。このプロパティは、現在の生成/変更プロセスのコンテキストでランタイムによって使用されます。 </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | テキストの文字間隔を取得します。 |
| [getCoordinateOrigin](#getCoordinateOrigin--) | テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。 |
| [getFont](#getFont--) | テキストのフォントを取得します。 |
| [getfontSize](#getfontSize--) | getfontSize メソッドを表します |
| [getFontSize](#getFontSize--) | テキストのフォントサイズを取得します。 |
| [getFontStyle](#getFontStyle--) | テキストのフォントスタイルを設定します。 |
| [getForegroundColor](#getForegroundColor--) | テキストの前景色を取得します。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> テキストの水平揃えを取得します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextState.HorizontalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | テキストの水平スケーリングを取得します。 |
| [getLineSpacing](#getLineSpacing--) | <p> テキストの行間を取得します。 </p> |
| [getRenderingMode](#getRenderingMode--) | テキストのレンダリングモードを取得または設定します。 |
| [getStrokingColor](#getStrokingColor--) | テキストの前景色を取得または設定します。 |
| [getTabTag](#getTabTag--) | <p> テキスト内にこのタグを配置してタブ設定を宣言できます。 </p> <hr> <p> {@code TabStops} と組み合わせた場合にのみ効果があります。 </p> |
| [getTextHeight](#getTextHeight--) | テキストの高さを取得します。 |
| [getWordSpacing](#getWordSpacing--) | テキストの単語間隔を取得します。 |
| [isInvisible](#isInvisible--) | テキストの不可視性を取得します。これは基本的に {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) の状態を反映しますが、クリッピングなどの特別なケースを除きます。 |
| [isStrikeOut](#isStrikeOut--) | テキストの取り消し線を取得します。これは {@code TextFragment} オブジェクトで表されます。 |
| [isSubscript](#isSubscript--) | テキストの下付き文字を取得または設定します。 |
| [isSuperscript](#isSuperscript--) | テキストの上付き文字を取得します。 |
| [isUnderline](#isUnderline--) | テキストの下線を取得します。これは {@code TextFragment} オブジェクトで表されます。 |
| [measureHeight](#measureHeight-char-) | 文字の高さを測定します。 |
| [measureString](#measureString-java.lang.String-) | 文字列を測定します。 |
| [measureString](#measureString-java.lang.String-boolean-) | <p> 文字列を測定します。 </p> <hr> <p> insideLine は文字列が終了していないことを示します。文字列の一部だけが測定される場合、insideLine は true にすべきです。文字列全体が測定される場合、insideLine は false にすべきです。言い換えれば、insideLine = true の場合は文字幅のみが考慮され、insideLine = false の場合は追加の変換は考慮されません。文字列の終端は適切に処理され、イタリック変換が考慮されます。 </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | テキストの背景色を設定します。 |
| [setCharacterSpacing](#setCharacterSpacing-float-) | テキストの文字間隔を設定します。 |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。 |
| [setFont](#setFont-com.aspose.pdf.Font-) | テキストのフォントを取得します。 |
| [setFontSize](#setFontSize-float-) | テキストのフォントサイズを設定します。 |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | テキストのフォントサイズを抑制された更新で設定します。 |
| [setFontStyle](#setFontStyle-int-) | テキストのフォントスタイルを設定します。 |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | テキストのフォントを抑制された更新で取得します。 |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | テキストの前景色を設定します。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> テキストの水平揃えを設定します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextState.HorizontalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | テキストの水平スケーリングを設定します。 |
| [setInvisible](#setInvisible-boolean-) | テキストの不可視性を設定します。これは基本的に {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) の状態を反映しますが、クリッピングなどの特別なケースを除きます。 |
| [setLineSpacing](#setLineSpacing-float-) | <p> テキストの行間を設定します。 </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | テキストのレンダリングモードを取得または設定します。 |
| [setStrikeOut](#setStrikeOut-boolean-) | テキストの取り消し線を設定します。これは {@code TextFragment} オブジェクトで表されます。 |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | テキストの前景色を取得または設定します。 |
| [setSubscript](#setSubscript-boolean-) | テキストの下付き文字を取得または設定します。 |
| [setSuperscript](#setSuperscript-boolean-) | テキストの上付き文字を設定します。 |
| [setUnderline](#setUnderline-boolean-) | テキストの下線を設定します。{@code TextFragment} オブジェクトで表されます |
| [setWordSpacing](#setWordSpacing-float-) | テキストの単語間隔を設定します。 |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

デフォルトフォントのスペース文字幅におけるタブ設定のデフォルト値。

### TextState {#TextState--}
```
public TextState()
```

テキストステートオブジェクトを作成します。

### TextState {#TextState-java.awt.Color-}
テキストステートオブジェクトを作成します。

### TextState {#TextState-java.awt.Color-double-}
テキストステートオブジェクトを作成します。

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

フォントサイズ指定付きのテキストステートオブジェクトを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontSize |  | フォントサイズ。 |

### TextState {#TextState-java.lang.String-}
テキストステートオブジェクトを作成します。

### TextState {#TextState-java.lang.String-boolean-boolean-}
テキストステートオブジェクトを作成します。

### TextState {#TextState-java.lang.String-double-}
テキストステートオブジェクトを作成します。

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> 別の textState から設定を適用します </p> <hr> <p> 明示的に変更されたプロパティのみがコピーされます。 </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
矩形のフォントサイズを計算します。

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> テキストの背景色を取得します。 </p> <hr> <p> この値はドキュメント内のテキスト特性として保持されないことに注意してください。BackgroundColor プロパティの getter は、対象オブジェクトに対して事前に BackgroundColor setter で明示的に設定されている場合に機能します。このプロパティは、現在の生成/変更プロセスのコンテキストでランタイムによって使用されます。 </p>

**Returns:**
カラー値

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

テキストの文字間隔を取得します。

**Returns:**
float 値

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。

**Returns:**
CoordinateOrigin 要素

### getFont {#getFont--}
```
public Font getFont()
```

テキストのフォントを取得します。

**Returns:**
フォントオブジェクト

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

getfontSize メソッドを表します

**Returns:**
float 値

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

テキストのフォントサイズを取得します。

**Returns:**
float 値

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

テキストのフォントスタイルを設定します。

**Returns:**
FontStyles 要素 @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

テキストの前景色を取得します。

**Returns:**
カラー値

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> テキストの水平揃えを取得します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextState.HorizontalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p>

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

テキストの水平スケーリングを取得します。

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
TextRenderingMode 要素 @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

テキストの前景色を取得または設定します。

**Returns:**
Color インスタンス

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> テキスト内にこのタグを配置してタブ設定を宣言できます。 </p> <hr> <p> {@code TabStops} と組み合わせた場合にのみ効果があります。 </p>

**Returns:**
文字列値 "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

テキストの高さを取得します。

**Returns:**
float 値

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

テキストの単語間隔を取得します。

**Returns:**
float 値

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

テキストの不可視性を取得します。これは基本的に {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) の状態を反映しますが、クリッピングなどの特別なケースを除きます。

**Returns:**
ブール値

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

テキストの取り消し線を取得します。これは {@code TextFragment} オブジェクトで表されます。

**Returns:**
ブール値

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

テキストの下付き文字を取得または設定します。

**Returns:**
ブール値

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

テキストの上付き文字を取得します。

**Returns:**
ブール値

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

テキストの下線を取得します。これは {@code TextFragment} オブジェクトで表されます。

**Returns:**
ブール値

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
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

### measureString {#measureString-java.lang.String-boolean-}
<p> 文字列を測定します。 </p> <hr> <p> insideLine は文字列が終了していないことを示します。文字列の一部だけが測定される場合、insideLine は true にすべきです。文字列全体が測定される場合、insideLine は false にすべきです。言い換えれば、insideLine = true の場合は文字幅のみが考慮され、insideLine = false の場合は追加の変換は考慮されません。文字列の終端は適切に処理され、イタリック変換が考慮されます。 </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
テキストの背景色を設定します。

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

テキストの文字間隔を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。その場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に選択できます。

### setFont {#setFont-com.aspose.pdf.Font-}
テキストのフォントを取得します。

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

テキストのフォントサイズを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

テキストのフォントサイズを抑制された更新で設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

テキストのフォントスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | FontStyles 値 @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
テキストのフォントを抑制された更新で取得します。

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
テキストの前景色を設定します。

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> テキストの水平揃えを設定します。 </p> <hr> <p> HorizontalAlignment.None は HorizontalAlignment.Left と同等です。TextState.HorizontalAlignment プロパティは新しいドキュメント生成シナリオでのみ機能することに注意してください。 </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

テキストの水平スケーリングを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

テキストの不可視性を設定します。これは基本的に {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) の状態を反映しますが、クリッピングなどの特別なケースを除きます。

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
テキストの前景色を取得または設定します。

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

テキストの下付き文字を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

テキストの上付き文字を設定します。

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
