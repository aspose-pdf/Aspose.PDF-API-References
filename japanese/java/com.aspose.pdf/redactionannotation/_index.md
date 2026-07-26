---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Redact 注釈を表します。"
type: docs
weight: 4120
url: /ja/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Redact 注釈を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | RedactionAnnotation のコンストラクタ。Generator で使用するためのものです。 |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | RedactAnnotation のコンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [flatten](#flatten--) | 注釈をフラット化します。つまり、注釈を削除し、その内容を追加します。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getBorderColor](#getBorderColor--) | redaction が非アクティブなときに描画される border の色を取得します。 |
| [getDefaultAppearance](#getDefaultAppearance--) | テキストの書式設定に使用される default appearance string を取得または設定します。 |
| [getFillColor](#getFillColor--) | 注釈を塗りつぶす色を取得します。 |
| [getFontSize](#getFontSize--) | OverlayText のフォントサイズを取得します。 |
| [getOverlayText](#getOverlayText--) | redact annotation に印刷するテキストを取得します。 |
| [getQuadPoint](#getQuadPoint--) | 削除対象となるコンテンツ領域の座標を指定する 8xN の数値配列です。 |
| [getQuadPoints](#getQuadPoints--) | n 個の四辺形の座標を指定するポイントの配列を取得します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。 |
| [getTextAlignment](#getTextAlignment--) | Overlay Text の配置を取得します。 |
| [isRepeat](#isRepeat--) | true の場合、overlay text が注釈上に繰り返されます。 |
| [redact](#redact--) | 注釈をフラット化し、ページ内容を赤字化します（つまり、redacted annotation の下にあるテキストと画像コンテンツを削除します）。 |
| [redactExact](#redactExact--) | 注釈をフラット化し、ページ内容を赤字化します（つまり、redacted annotation の正確な下にあるテキストと画像コンテンツを削除します）。 |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | redaction が非アクティブなときに描画される border の色を設定します。 |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | テキストの書式設定に使用される default appearance string を取得または設定します。 |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | 注釈を塗りつぶす色を設定します。 |
| [setFontSize](#setFontSize-float-) | OverlayText のフォントサイズを設定します。デフォルト値は 10 です。 |
| [setOverlayText](#setOverlayText-java.lang.String-) | redact annotation に印刷するテキストを設定します。 |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | 削除対象となるコンテンツ領域の座標を指定する 8xN の数値配列です。 |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | n 個の四辺形の座標を指定するポイントの配列を設定します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。 |
| [setRepeat](#setRepeat-boolean-) | true の場合、overlay text が注釈上に繰り返されます。 |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Overlay Text の配置を設定します。 |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
RedactionAnnotation のコンストラクタ。Generator で使用するためのものです。

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
RedactAnnotation のコンストラクタ。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### flatten {#flatten--}
```
public void flatten()
```

注釈をフラット化します。つまり、注釈を削除し、その内容を追加します。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

redaction が非アクティブなときに描画される border の色を取得します。

**Returns:**
カラー値

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

テキストの書式設定に使用される default appearance string を取得または設定します。

**Returns:**
文字列値

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

注釈を塗りつぶす色を取得します。

**Returns:**
色の値

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

OverlayText のフォントサイズを取得します。

**Returns:**
int 値です。

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

redact annotation に印刷するテキストを取得します。

**Returns:**
string 値

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

削除対象となるコンテンツ領域の座標を指定する 8xN の数値配列です。

**Returns:**
ポイントの配列

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

n 個の四辺形の座標を指定するポイントの配列を取得します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。

**Returns:**
Point 値の配列

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Overlay Text の配置を取得します。

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

true の場合、overlay text が注釈上に繰り返されます。

**Returns:**
ブール値

### redact {#redact--}
```
public void redact()
```

注釈をフラット化し、ページ内容を赤字化します（つまり、redacted annotation の下にあるテキストと画像コンテンツを削除します）。

### redactExact {#redactExact--}
```
public void redactExact()
```

注釈をフラット化し、ページ内容を赤字化します（つまり、redacted annotation の正確な下にあるテキストと画像コンテンツを削除します）。

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
redaction が非アクティブなときに描画される border の色を設定します。

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
テキストの書式設定に使用される default appearance string を取得または設定します。

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
注釈を塗りつぶす色を設定します。

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

OverlayText のフォントサイズを設定します。デフォルト値は 10 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontSize |  | int 値です。 |

### setOverlayText {#setOverlayText-java.lang.String-}
redact annotation に印刷するテキストを設定します。

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
削除対象となるコンテンツ領域の座標を指定する 8xN の数値配列です。

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
n 個の四辺形の座標を指定するポイントの配列を設定します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

true の場合、overlay text が注釈上に繰り返されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Overlay Text の配置を設定します。
