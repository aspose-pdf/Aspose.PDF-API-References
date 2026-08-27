---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ポリ注釈用の抽象基底クラスです。"
type: docs
weight: 3890
url: /ja/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

ポリ注釈用の抽象基底クラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 行列変換に従って Vertices のポイントを更新します。 |
| [getEndingStyle](#getEndingStyle--) | 第2ラインエンドのスタイルを取得します。 |
| [getIntent](#getIntent--) | ポリゴンまたはポリライン注釈の意図を取得します。 |
| [getInteriorColor](#getInteriorColor--) | 注釈のラインエンドを塗りつぶす内部色を取得します。 |
| [getMeasure](#getMeasure--) | この注釈に指定された測定単位。 |
| [getStartingStyle](#getStartingStyle--) | 第1ラインエンドのスタイルを取得します。 |
| [getVertices](#getVertices--) | 各頂点の水平および垂直座標を表すポイントの配列を取得します。 |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | 第2のラインエンドのスタイルを設定します。 |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | ポリゴンまたはポリライン注釈の意図を設定します。 |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | 注釈のラインエンドを塗りつぶすための内部色を設定します。 |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | この注釈に指定された測定単位。 |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | 第1のラインエンドのスタイルを設定します。 |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | 各頂点の水平および垂直座標を表すポイントの配列を設定します。 |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
行列変換に従って Vertices のポイントを更新します。

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

第2ラインエンドのスタイルを取得します。

**Returns:**
LineEnding 要素 @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

ポリゴンまたはポリライン注釈の意図を取得します。

**Returns:**
PolyIntent 要素 @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

注釈のラインエンドを塗りつぶす内部色を取得します。

**Returns:**
Color オブジェクト

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

この注釈に指定された測定単位。

**Returns:**
Measure インスタンス

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

第1ラインエンドのスタイルを取得します。

**Returns:**
LineEnding 要素 @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

各頂点の水平および垂直座標を表すポイントの配列を取得します。

**Returns:**
Point 値の配列

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
第2のラインエンドのスタイルを設定します。

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
ポリゴンまたはポリライン注釈の意図を設定します。

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
注釈のラインエンドを塗りつぶすための内部色を設定します。

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
この注釈に指定された測定単位。

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
第1のラインエンドのスタイルを設定します。

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
各頂点の水平および垂直座標を表すポイントの配列を設定します。
