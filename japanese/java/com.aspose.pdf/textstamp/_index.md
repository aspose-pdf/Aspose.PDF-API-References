---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストスタンプを表します。"
type: docs
weight: 5320
url: /ja/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

テキストスタンプを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | formattedText オブジェクトを使用して {@code TextStamp} クラスの新しいインスタンスを初期化します。 |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | formattedText オブジェクトを使用して {@code TextStamp} クラスの新しいインスタンスを初期化します。 |
| [TextStamp](#TextStamp-java.lang.String-) | {@code TextStamp} クラスの新しいインスタンスを初期化します。 |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | TextStamp クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | フォントサイズの精度を自動的に調整します。デフォルト値: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | 有効にすると、フォントサイズはスタンプ矩形のサイズに合わせて自動的に調整されます: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) と {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。デフォルトの幅と高さはページ矩形から導出されます。 |
| [getDefaultFont](#getDefaultFont--) | デフォルトフォントを返します |
| [getDefaultFontSize](#getDefaultFontSize--) | デフォルトフォントサイズ |
| [getDraw](#getDraw--) | このプロパティは、ページ上にスタンプが描画される方法を決定します。Draw = true の場合、スタンプはグラフィックオペレーターとして描画され、draw = false の場合、スタンプはテキストとして描画されます。 |
| [getFontSize](#getFontSize--) | スタンプが配置された後の実際のフォントサイズです。（'AutoAdjustFontSizeToFitStampRectangle' オプションが有効な場合、コンストラクターで提供された初期フォントサイズと異なる可能性があります。） |
| [getHeight](#getHeight--) | ページ上のスタンプの希望高さです。 |
| [getMaxRowWidth](#getMaxRowWidth--) | WordWrap オプションの最大行高さです。 |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | フォントに要求された文字が含まれていない場合の動作を定義するモードを取得または設定します。 |
| [getReplacementFont](#getReplacementFont--) | ユーザーフォントに必要な文字が含まれていない場合に置き換えるために使用されるフォントを取得または設定します。 |
| [getTextAlignment](#getTextAlignment--) | スタンプ内のテキストの配置。 |
| [getTextState](#getTextState--) | スタンプのテキストプロパティを取得します。詳細は {@code TextState} を参照してください。 |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | テキスト配置の座標原点を定義します。TreatYIndentAsBaseLine = true（Draw = true のデフォルト）の場合、YIndent の値はテキストのベースラインとして扱われます。TreatYIndentAsBaseLine = false（Draw = false のデフォルト）の場合、YIndent の値はテキストの底部（ディセントライン）として扱われます。 |
| [getValue](#getValue--) | ページ上のスタンプとして使用される文字列値を取得します。 |
| [getWidth](#getWidth--) | ページ上のスタンプの希望幅です。 |
| [getWordWrapMode](#getWordWrapMode--) | テキスト描画のワードラップモードを取得または設定します。 |
| [isJustify](#isJustify--) | テキストの両端揃えを定義します。このプロパティが true に設定されている場合、テキストの左端と右端が揃えられます。デフォルト値: false。 |
| [isScale](#isScale--) | テキストのスケーリングを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に合わせて拡大縮小されます。 |
| [isWordWrap](#isWordWrap--) | ワードラップを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に収まるよう複数行に分割されます。デフォルト値: false。 |
| [put](#put-com.aspose.pdf.Page-) | ページにテキストスタンプを追加します。 |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | フォントサイズの精度を自動的に調整します。デフォルト値: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | 有効にすると、フォントサイズはスタンプ矩形のサイズに合わせて自動的に調整されます: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) と {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。デフォルトの幅と高さはページ矩形から導出されます。 |
| [setDraw](#setDraw-boolean-) | このプロパティは、ページ上にスタンプが描画される方法を決定します。Draw = true の場合、スタンプはグラフィックオペレーターとして描画され、draw = false の場合、スタンプはテキストとして描画されます。 |
| [setHeight](#setHeight-double-) | ページ上のスタンプの希望高さです。 |
| [setJustify](#setJustify-boolean-) | テキストの両端揃えを定義します。このプロパティが true に設定されている場合、テキストの左端と右端が揃えられます。デフォルト値: false。 |
| [setMaxRowWidth](#setMaxRowWidth-double-) | WordWrap オプションの最大行高さです。 |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | フォントに要求された文字が含まれていない場合の動作を定義するモードを取得または設定します。 |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | ユーザーフォントに必要な文字が含まれていない場合に置き換えるために使用されるフォントを取得または設定します。 |
| [setScale](#setScale-boolean-) | テキストのスケーリングを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に合わせて拡大縮小されます。 |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | スタンプ内のテキストの配置。 |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | テキスト配置の座標原点を定義します。TreatYIndentAsBaseLine = true（Draw = true のデフォルト）の場合、YIndent の値はテキストのベースラインとして扱われます。TreatYIndentAsBaseLine = false（Draw = false のデフォルト）の場合、YIndent の値はテキストの底部（ディセントライン）として扱われます。 |
| [setValue](#setValue-java.lang.String-) | ページ上のスタンプとして使用される文字列値を設定します。 |
| [setWidth](#setWidth-double-) | ページ上のスタンプの希望幅です。 |
| [setWordWrap](#setWordWrap-boolean-) | ワードラップを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に収まるよう複数行に分割されます。デフォルト値: false。 |
| [setWordWrapMode](#setWordWrapMode-int-) | テキスト描画のワードラップモードを取得または設定します。 |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
formattedText オブジェクトを使用して {@code TextStamp} クラスの新しいインスタンスを初期化します。

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
formattedText オブジェクトを使用して {@code TextStamp} クラスの新しいインスタンスを初期化します。

### TextStamp {#TextStamp-java.lang.String-}
{@code TextStamp} クラスの新しいインスタンスを初期化します。

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
TextStamp クラスの新しいインスタンスを初期化します。

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

フォントサイズの精度を自動的に調整します。デフォルト値: 0.1;

**Returns:**
float 値

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

有効にすると、フォントサイズはスタンプ矩形のサイズに合わせて自動的に調整されます: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) と {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。デフォルトの幅と高さはページ矩形から導出されます。

**Returns:**
ブール値

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

デフォルトフォントを返します

**Returns:**
com.aspose.pdf.Font object

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

デフォルトフォントサイズ

**Returns:**
float 値

### getDraw {#getDraw--}
```
public boolean getDraw()
```

このプロパティは、ページ上にスタンプが描画される方法を決定します。Draw = true の場合、スタンプはグラフィックオペレーターとして描画され、draw = false の場合、スタンプはテキストとして描画されます。

**Returns:**
ブール値

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

スタンプが配置された後の実際のフォントサイズです。（'AutoAdjustFontSizeToFitStampRectangle' オプションが有効な場合、コンストラクターで提供された初期フォントサイズと異なる可能性があります。）

**Returns:**
float 値

### getHeight {#getHeight--}
```
public double getHeight()
```

ページ上のスタンプの希望高さです。

**Returns:**
double 値

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

WordWrap オプションの最大行高さです。

**Returns:**
double 値

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

フォントに要求された文字が含まれていない場合の動作を定義するモードを取得または設定します。

**Returns:**
NoCharacterAction 要素

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

ユーザーフォントに必要な文字が含まれていない場合に置き換えるために使用されるフォントを取得または設定します。

**Returns:**
フォント インスタンス

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

スタンプ内のテキストの配置。

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

スタンプのテキストプロパティを取得します。詳細は {@code TextState} を参照してください。

**Returns:**
TextState 要素

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

テキスト配置の座標原点を定義します。TreatYIndentAsBaseLine = true（Draw = true のデフォルト）の場合、YIndent の値はテキストのベースラインとして扱われます。TreatYIndentAsBaseLine = false（Draw = false のデフォルト）の場合、YIndent の値はテキストの底部（ディセントライン）として扱われます。

**Returns:**
ブール値

### getValue {#getValue--}
```
public String getValue()
```

ページ上のスタンプとして使用される文字列値を取得します。

**Returns:**
文字列値

### getWidth {#getWidth--}
```
public double getWidth()
```

ページ上のスタンプの希望幅です。

**Returns:**
double 値

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

テキスト描画のワードラップモードを取得または設定します。

**Returns:**
WordWrapMode 要素

### isJustify {#isJustify--}
```
public boolean isJustify()
```

テキストの両端揃えを定義します。このプロパティが true に設定されている場合、テキストの左端と右端が揃えられます。デフォルト値: false。

**Returns:**
ブール値

### isScale {#isScale--}
```
public boolean isScale()
```

テキストのスケーリングを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に合わせて拡大縮小されます。

**Returns:**
ブール値

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

ワードラップを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に収まるよう複数行に分割されます。デフォルト値: false。

**Returns:**
ブール値 @deprecated "WordWrapMode を代わりに使用してください。"

### put {#put-com.aspose.pdf.Page-}
ページにテキストスタンプを追加します。

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

フォントサイズの精度を自動的に調整します。デフォルト値: 0.1;

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

有効にすると、フォントサイズはスタンプ矩形のサイズに合わせて自動的に調整されます: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) と {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。デフォルトの幅と高さはページ矩形から導出されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

このプロパティは、ページ上にスタンプが描画される方法を決定します。Draw = true の場合、スタンプはグラフィックオペレーターとして描画され、draw = false の場合、スタンプはテキストとして描画されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

ページ上のスタンプの希望高さです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

テキストの両端揃えを定義します。このプロパティが true に設定されている場合、テキストの左端と右端が揃えられます。デフォルト値: false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

WordWrap オプションの最大行高さです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

フォントに要求された文字が含まれていない場合の動作を定義するモードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | NoCharacterAction 要素 |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
ユーザーフォントに必要な文字が含まれていない場合に置き換えるために使用されるフォントを取得または設定します。

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

テキストのスケーリングを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に合わせて拡大縮小されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
スタンプ内のテキストの配置。

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

テキスト配置の座標原点を定義します。TreatYIndentAsBaseLine = true（Draw = true のデフォルト）の場合、YIndent の値はテキストのベースラインとして扱われます。TreatYIndentAsBaseLine = false（Draw = false のデフォルト）の場合、YIndent の値はテキストの底部（ディセントライン）として扱われます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setValue {#setValue-java.lang.String-}
ページ上のスタンプとして使用される文字列値を設定します。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

ページ上のスタンプの希望幅です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

ワードラップを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に収まるよう複数行に分割されます。デフォルト値: false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 @deprecated "WordWrapMode を代わりに使用してください。" |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

テキスト描画のワードラップモードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | WordWrapMode 要素 @see WordWrapMode |
