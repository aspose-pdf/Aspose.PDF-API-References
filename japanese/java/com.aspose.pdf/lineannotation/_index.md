---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ライン注釈を表すクラスです。"
type: docs
weight: 2710
url: /ja/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

ライン注釈を表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Generator と共に使用するためのコンストラクタです。 |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | 指定されたページに新しい Line アノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | アノテーション処理のためのビジターを受け入れます。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 行列変換に従って開始点と終了点を更新します。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getCaptionOffset](#getCaptionOffset--) | キャプションテキストのオフセットを通常位置から取得します。 |
| [getCaptionPosition](#getCaptionPosition--) | アノテーションのキャプション位置を取得します。 |
| [getEnding](#getEnding--) | 線の終了点を取得します。 |
| [getEndingStyle](#getEndingStyle--) | 線の終点の終了スタイルを取得します。 |
| [getIntent](#getIntent--) | ラインアノテーションの意図を取得します。 |
| [getInteriorColor](#getInteriorColor--) | 注釈の内部色を取得します。 |
| [getLeaderLine](#getLeaderLine--) | リーダーラインの長さを取得します。 |
| [getLeaderLineExtension](#getLeaderLineExtension--) | リーダーライン拡張の長さを取得します。 |
| [getLeaderLineOffset](#getLeaderLineOffset--) | リーダーラインのオフセットを取得します。 |
| [getMeasure](#getMeasure--) | この注釈に指定された測定単位です。 |
| [getShowCaption](#getShowCaption--) | 内容をキャプションとして表示するかどうかを決定するブールフラグを取得します。 |
| [getStarting](#getStarting--) | 線の開始点を取得します。 |
| [getStartingStyle](#getStartingStyle--) | 線の開始点に対する終端スタイルを取得します。 |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | キャプションテキストの通常位置からのオフセットを設定します。 |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | 注釈のキャプション位置を設定します。 |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | 線の終点を設定します。 |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | 線の終点に対する終端スタイルを設定します。 |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | 線注釈の意図を設定します。 |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | 注釈の内部色を設定します。 |
| [setLeaderLine](#setLeaderLine-double-) | リーダーラインの長さを設定します。 |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | リーダーライン拡張の長さを設定します。 |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | リーダーラインのオフセットを設定します。 |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | この注釈に指定された測定単位です。 |
| [setShowCaption](#setShowCaption-boolean-) | 内容をキャプションとして表示するかどうかを決定するブールフラグを設定します。 |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | 線の開始点を設定します。 |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | 線の開始点に対する終端スタイルを設定します。 |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Generator と共に使用するためのコンストラクタです。

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
指定されたページに新しい Line アノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
アノテーション処理のためのビジターを受け入れます。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
行列変換に従って開始点と終了点を更新します。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

キャプションテキストのオフセットを通常位置から取得します。

**Returns:**
Point オブジェクト

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

アノテーションのキャプション位置を取得します。

**Returns:**
CaptionPosition 要素 @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

線の終了点を取得します。

**Returns:**
ポイント値

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

線の終点の終了スタイルを取得します。

**Returns:**
LineEnding 要素 @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

ラインアノテーションの意図を取得します。

**Returns:**
LineIntent 要素 @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

注釈の内部色を取得します。

**Returns:**
Color オブジェクト

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

リーダーラインの長さを取得します。

**Returns:**
double 値

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

リーダーライン拡張の長さを取得します。

**Returns:**
double 値

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

リーダーラインのオフセットを取得します。

**Returns:**
double 値

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

この注釈に指定された測定単位です。

**Returns:**
測定オブジェクト

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

内容をキャプションとして表示するかどうかを決定するブールフラグを取得します。

**Returns:**
ブール値

### getStarting {#getStarting--}
```
public Point getStarting()
```

線の開始点を取得します。

**Returns:**
ポイント値

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

線の開始点に対する終端スタイルを取得します。

**Returns:**
LineEnding 要素 @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
キャプションテキストの通常位置からのオフセットを設定します。

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
注釈のキャプション位置を設定します。

### setEnding {#setEnding-com.aspose.pdf.Point-}
線の終点を設定します。

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
線の終点に対する終端スタイルを設定します。

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
線注釈の意図を設定します。

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
注釈の内部色を設定します。

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

リーダーラインの長さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

リーダーライン拡張の長さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

リーダーラインのオフセットを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
この注釈に指定された測定単位です。

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

内容をキャプションとして表示するかどうかを決定するブールフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setStarting {#setStarting-com.aspose.pdf.Point-}
線の開始点を設定します。

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
線の開始点に対する終端スタイルを設定します。
