---
title: "Curve"
linktitle: "Curve"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ベジエ曲線を表します。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

ベジエ曲線を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Curve](#Curve--) | 内部使用のみ |
| [Curve](#Curve-float:A-) | {@code Curve} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getPositionArray](#getPositionArray--) | float の位置配列を取得します。 |
| [setPositionArray](#setPositionArray-float:A-) | float の位置配列を設定します。 |

### Curve {#Curve--}
```
public Curve()
```

内部使用のみ

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

{@code Curve} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| positionArray |  | 曲線の制御点の位置配列です。制御点は4つ必要なため、配列の長さは8になる必要があります。 |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
適合する場合は true、そうでない場合は false。

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

float の位置配列を取得します。

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

float の位置配列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float[] array |
