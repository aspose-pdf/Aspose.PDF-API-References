---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> テキスト段落を複数行テキストオブジェクトとして表します。 </p> <hr> <pre> 例では、テキスト段落オブジェクトを作成し、Pdf ページに追加する方法を示しています。 Document doc."
type: docs
weight: 5200
url: /ja/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> テキスト段落を複数行テキストオブジェクトとして表します。 </p> <hr> <pre> この例は、テキスト段落オブジェクトを作成し、Pdf ページに追加する方法を示しています。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // テキスト段落を作成 TextParagraph paragraph = new TextParagraph(); // 段落の矩形を設定 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // 単語折り返しオプションを設定 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // 文字列行を追加 paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // TextBuilder を使用して段落を Pdf ページに追加 TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // Pdf ドキュメントを保存 doc.save(outFile); </pre>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextParagraph](#TextParagraph--) | {@code TextParagraph} オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | テキスト行を追加します |
| [appendLine](#appendLine-java.lang.String-float-) | テキスト行を追加します。 |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | テキスト状態パラメータ付きのテキスト行を追加します。 |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | テキスト状態パラメータ付きのテキスト行を追加します |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | テキスト状態パラメータ付きのテキスト行を追加します。 |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | テキスト状態パラメータ付きのテキスト行を追加します。 |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | テキスト状態パラメータ付きのテキスト行を追加します |
| [beginEdit](#beginEdit--) | TextParagraph の編集を開始します。 <p> TextParagraph の生成パフォーマンスを向上させます。レイアウト計算は EndEdit メソッドが呼び出されるまで保留されます。 <p> メソッド呼び出しは入れ子にできないことに注意してください。 </p> |
| [endEdit](#endEdit--) | TextParagraph の編集を終了します。 <p> TextParagraph の生成パフォーマンスを向上させます。レイアウト計算は EndEdit メソッドが呼び出されるまで保留されます。 <p> メソッド呼び出しは入れ子にできないことに注意してください。 </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | 次行インデント値を取得または設定します。0 以外の値に設定すると、FormattingOptions.SubsequentLinesIndent の値よりも優位性があります。 |
| [getFormattingOptions](#getFormattingOptions--) | 書式設定オプションを取得します。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 段落の Rectangle 内のテキストの水平揃えを取得します。HorizontalAlignment.None は HorizontalAlignment.Left と同等です。 |
| [getHyphenSymbol](#getHyphenSymbol--) | ハイフン化プロセスで使用されるハイフン記号を取得します。ハイフン化記号はデフォルトで "-" です。ハイフンの描画を除去したい場合（折り返し処理は維持したまま）、HyphenSymbol に空文字列 string.Empty を設定してください。 |
| [getMargin](#getMargin--) | 余白を取得します。 |
| [getPosition](#getPosition--) | 段落の位置を取得します。 |
| [getRectangle](#getRectangle--) | 段落の矩形を取得します。 |
| [getRotation](#getRotation--) | 回転角度（度単位）を取得または設定します。 |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | 次行のインデント値を取得します。 |
| [getTextRectangle](#getTextRectangle--) | 段落に配置されたテキストの矩形を取得します。 |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> 段落の {@code Rectangle} 内のテキストの垂直揃えを取得します。 </p> |
| [isJustify](#isJustify--) | テキストが両端揃えかどうかの値を取得します。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | テキスト段落の背景色を設定します。 |
| [setBackgroundMode](#setBackgroundMode-int-) | テキスト段落の背景モードを設定します |
| [setFirstLineIndent](#setFirstLineIndent-float-) | 次行インデント値を取得または設定します。0 以外の値に設定すると、FormattingOptions.SubsequentLinesIndent の値よりも優位性があります。 |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | 書式設定オプションを設定します。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 段落の Rectangle 内のテキストの水平揃えを設定します。HorizontalAlignment.None は HorizontalAlignment.Left と同等です。 |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | ハイフン化プロセスで使用されるハイフン記号を設定します。ハイフン化記号はデフォルトで "-" です。ハイフンの描画を除去したい場合（折り返し処理は維持したまま）、HyphenSymbol に空文字列 string.Empty を設定してください。 |
| [setJustify](#setJustify-boolean-) | テキストが両端揃えかどうかの値を設定します。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 余白を設定します。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 段落の回転を設定します。 |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | 古いコード互換モードを設定します |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | 段落の位置を設定します。 |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | 段落の矩形を設定します。 |
| [setRotation](#setRotation-double-) | 回転角度（度単位）を取得または設定します。 |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | 次行のインデント値を設定します。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 段落の {@code Rectangle} 内のテキストの垂直揃えを設定します。VerticalAlignment.None は VerticalAlignment.Bottom と同等です。 |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

{@code TextParagraph} オブジェクトを作成します。

### appendLine {#appendLine-java.lang.String-}
テキスト行を追加します

### appendLine {#appendLine-java.lang.String-float-}
テキスト行を追加します。

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
テキスト状態パラメータ付きのテキスト行を追加します。

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
テキスト状態パラメータ付きのテキスト行を追加します

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
テキスト状態パラメータ付きのテキスト行を追加します。

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
テキスト状態パラメータ付きのテキスト行を追加します。

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
テキスト状態パラメータ付きのテキスト行を追加します

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

TextParagraph の編集を開始します。 <p> TextParagraph の生成パフォーマンスを向上させます。レイアウト計算は EndEdit メソッドが呼び出されるまで保留されます。 <p> メソッド呼び出しは入れ子にできないことに注意してください。 </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

TextParagraph の編集を終了します。 <p> TextParagraph の生成パフォーマンスを向上させます。レイアウト計算は EndEdit メソッドが呼び出されるまで保留されます。 <p> メソッド呼び出しは入れ子にできないことに注意してください。 </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

次行インデント値を取得または設定します。0 以外の値に設定すると、FormattingOptions.SubsequentLinesIndent の値よりも優位性があります。

**Returns:**
float 値

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

書式設定オプションを取得します。

**Returns:**
TextFormattingOptions オブジェクト

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

段落の Rectangle 内のテキストの水平揃えを取得します。HorizontalAlignment.None は HorizontalAlignment.Left と同等です。

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

ハイフン化プロセスで使用されるハイフン記号を取得します。ハイフン化記号はデフォルトで "-" です。ハイフンの描画を除去したい場合（折り返し処理は維持したまま）、HyphenSymbol に空文字列 string.Empty を設定してください。

**Returns:**
文字列値

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

余白を取得します。

**Returns:**
MarginInfo 値

### getPosition {#getPosition--}
```
public Position getPosition()
```

段落の位置を取得します。

**Returns:**
位置の値

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

段落の矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getRotation {#getRotation--}
```
public double getRotation()
```

回転角度（度単位）を取得または設定します。

**Returns:**
double 値

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

次行のインデント値を取得します。

**Returns:**
float 値

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

段落に配置されたテキストの矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> 段落の {@code Rectangle} 内のテキストの垂直揃えを取得します。 </p>

**Returns:**
VerticalAlignment の値 @see VerticalAlignment <hr> <p> VerticalAlignment.None は VerticalAlignment.Bottom と同等です。 </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

テキストが両端揃えかどうかの値を取得します。

**Returns:**
ブール値

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
テキスト段落の背景色を設定します。

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

テキスト段落の背景モードを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

次行インデント値を取得または設定します。0 以外の値に設定すると、FormattingOptions.SubsequentLinesIndent の値よりも優位性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
書式設定オプションを設定します。

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
段落の Rectangle 内のテキストの水平揃えを設定します。HorizontalAlignment.None は HorizontalAlignment.Left と同等です。

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
ハイフン化プロセスで使用されるハイフン記号を設定します。ハイフン化記号はデフォルトで "-" です。ハイフンの描画を除去したい場合（折り返し処理は維持したまま）、HyphenSymbol に空文字列 string.Empty を設定してください。

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

テキストが両端揃えかどうかの値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
余白を設定します。

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
段落の回転を設定します。

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

古いコード互換モードを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPosition {#setPosition-com.aspose.pdf.Position-}
段落の位置を設定します。

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
段落の矩形を設定します。

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

回転角度（度単位）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

次行のインデント値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
段落の {@code Rectangle} 内のテキストの垂直揃えを設定します。VerticalAlignment.None は VerticalAlignment.Bottom と同等です。
