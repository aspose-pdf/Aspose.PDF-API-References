---
title: "Line"
linktitle: "Line"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "線を表します。"
type: docs
weight: 90
url: /ja/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

線を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Line](#Line--) | 内部使用のみ |
| [Line](#Line-float:A-) | {@code Line} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getPositionArray](#getPositionArray--) | 位置配列を示すオブジェクトを取得します。配列は、直線の各制御点の座標で構成されています。 |
| [setPositionArray](#setPositionArray-float:A-) | 位置配列を示すオブジェクトを設定します。配列は、直線の各制御点の座標で構成されています。 |

### Line {#Line--}
```
public Line()
```

内部使用のみ

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

{@code Line} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| positionArray |  | 直線の位置配列。 |

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

位置配列を示すオブジェクトを取得します。配列は、直線の各制御点の座標で構成されています。

**Returns:**
位置配列を示す。

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

位置配列を示すオブジェクトを設定します。配列は、直線の各制御点の座標で構成されています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 位置配列を示す。 |
